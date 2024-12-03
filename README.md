# Umamusume: Pretty Derby resources unpack 

> [!Warning]
> Large repository.

> [!CAUTION]
> Only for personal use. Cygames, Inc. All Rights Reserved.

Credit: [umamusume-voice-text-extractor](https://github.com/chinosk6/umamusume-voice-text-extractor)

Right, this mma code was written so long time ago that I've forgotten what it was meant to do...

Seems that it'll flatten the directory structure and reorganize dialogue script file to align with training requirements.

```
├─character_system_text
│  └─1003
│      ├─snd_voi_aimteam_100300
│      │      0.wav

↓ flatten

character_system_text_1003_snd_voi_aimteam_100300_0.wav
```

```
story/data/09/0001/storytimeline_090001003/29.wav|まずここが学内ジム！　あ、器具はもちろんウマ娘仕様だから、 パワー全開でやっちゃって大丈夫だよ♪

↓ flatten

./dataset/Teio/story_data_09_0001_storytimeline_090001003_29.wav|Teio|JP|まずここが学内ジム！　あ、器具はもちろんウマ娘仕様だから、 パワー全開でやっちゃって大丈夫だよ♪
```

This repo needs refinement.

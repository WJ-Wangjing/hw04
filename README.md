# hw04
音频
hw04大模型文案、剪映声音克隆与开源语音识别实践

任务一:
详见text_gen.md

任务二:
剪映产出说明
克隆步骤概要：①录一段大于五秒小于十秒的音，保存为音频格式；②将音频上传至剪映即梦；③将任务一的文字复制到输入框，点击生成即可。
导出文件格式：mp3

任务三:
安装与运行说明
①环境配置-Anaconda环境
conda create-n asr_env python=3.11-y
conda activate asr_env
②安装核心依赖
conda install -c conda-forge ffmpeg pyaudio numpy=2.3.1-y
pip install -r requirements.txt
③运行脚本
cd C:\Users\32414\Desktop\asr_project
④音频文件识别（替换test.wav为你的音频）
python asr_file.py
⑤麦克风实时识别
python asr_realtime.py

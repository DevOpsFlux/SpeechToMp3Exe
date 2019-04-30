# SpeechToMp3Test
Speech To Mp3 Make File Test


## 1. ������Ʈ ���� �� ����

### *[ SpeechToMp3Test Solution ]	

| ������Ʈ | ���� | .NET���� | SpeechToMp3Test���� |
| -------- | -------- | -------- | -------- |
| SpeechToMp3Test | Speech To Mp3 Make | .NET 4.0	| SpeechToMp3Test.exe 1.0.0.0 |

## 2. ������Ʈ ���� �� ����
- reference System.Speech
 - using System.Speech.Synthesis;
- reference Nuget Package NAudio.Lame
 - using NAudio.Wave;
 - using NAudio.Lame; 

## 3. ���� ���� ��ġ ���� ���� �� ���� ����
- Windows Server ��������(TTS) ���� ��� �߰�
- ��ġ ��� : 32/64bit ������ �������
```
1. SpeechPlatformRuntime
	SpeechPlatformRuntime(x86).msi
	SpeechPlatformRuntime(x64).msi
	https://www.microsoft.com/en-us/download/details.aspx?id=27225

2. MicrosoftSpeechPlatformSDK
	MicrosoftSpeechPlatformSDK(x86).msi
	MicrosoftSpeechPlatformSDK(x64).msi
	https://www.microsoft.com/en-us/download/details.aspx?id=27226

3. MSSpeech_TTS_ko-KR_Heami.msi
	http://download.microsoft.com/download/4/0/D/40D6347A-AFA5-417D-A9BB-173D937BEED4/MSSpeech_TTS_ko-KR_Heami.msi
4. MSSpeech_TTS_en-US_Helen.msi
	https://www.microsoft.com/en-us/download/details.aspx?id=27224
```

## 4. ����
* \bin\Release\WE3H60_Mp3.mp3

![Monitor](./img/mp3make.JPG)

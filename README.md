# extail-evaluation-202203

We conducted a questionnaire survey on the dynamic expression of hair by Extail.

## Survey Summary
Participants watched [videos of eight movement patterns](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/README.md#%E8%A9%95%E4%BE%A1%E5%AF%BE%E8%B1%A1)with various combinations of swing amplitude, speed, and turn waiting time and responded. 
 
## Method of Survey
- Implementation period: 2022/03/01-2022/03/25
- Survey method: Web-based survey using Google Forms, an Internet-based questionnaire creation form.
- Distribution channels:
    - QR code for response form presented in a corner of the exhibition at the Tokyo Metropolitan University Graduation Works Exhibition 2022.
    - Provide the URL to the response form via Twitter and the slack community I belong to.
- Number of respondents: 9

## Movement to be evaluated
### pattern1
![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/pattern_1.gif)
### pattern2
![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/pattern_2.gif)
### pattern3
![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/pattern_3.gif)
### pattern4
![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/pattern_4.gif)
### pattern5
![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/pattern_5.gif)
### pattern6
![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/pattern_6.gif)
### pattern7
![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/pattern_7.gif)
### pattern8
![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/pattern_8.gif)
## 結果
Each parameter is set within the following ranges.
- Amplitude（5〜70）: Rotation angle of stepper motor shaft, equivalent to 15 to 210 degrees
- Speed（2〜8）： Equivalent to the interval between steps on the shaft of the stepper motor; the unit is ms; the higher the value, the slower the motor rotates.
- Turn waiting time（0〜10000[ms]）: The time it takes for the stepper motor to swing off to one side at a certain amplitude and then start moving in the opposite direction.

![image](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/result.png)

| Operation Pattern |      Amplitude      | Turn waiting time |
| :---------------- | :-----------------: | ----------------: |
| hoge              | Ultra-small<br>[10] |       High<br>[2] | None<br>[0] | Upset, Fear, Surprised, Scared, Thrilled, nervous |
| hoge              |          ^          |                 ^ |
| hoge              |          ^          |                 ^ |
| hoge              |                     |              piyo |
| ^                 |          ^          |              piyo |

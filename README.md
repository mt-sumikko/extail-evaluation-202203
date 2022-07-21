# extail-evaluation-202203

We conducted a questionnaire survey on the dynamic expression of hair by Extail.

## Survey Summary
Participants watched [videos of eight movement patterns](https://github.com/mt-sumikko/extail-evaluation-202203/blob/main/README.md#%E8%A9%95%E4%BE%A1%E5%AF%BE%E8%B1%A1) with various combinations of swing amplitude, speed, and turn waiting time and responded  in an open-ended format to what the wearer appeared to be.
 
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
## Result
Each parameter is set within the following ranges.
- Amplitude（15-210[degrees]）: Rotation angle of stepper motor shaft. The higher the value, the larger the amplitude.
- Speed（2-8[ms]）： Equivalent to the interval between steps on the shaft of the stepper motor; the unit is ms; the higher the value, the slower the motor rotates.
- Turn waiting time（0-10000[ms]）: The time it takes for the stepper motor to swing off to one side at a certain amplitude and then start moving in the opposite direction.

| Operation Pattern |       Amplitude        |        Speed         |  Turn waiting time  | Answer (What state does the person wearing Extail appear to be in?)                                                                                              |
| :---------------: | :--------------------: | :------------------: | :-----------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|         1         |   30<br>(Very Small)   |     2<br>(High)      |     0<br>(None)     | "Upset", "Fear", "Surprised", "Scared", "Thrilled", "Nervous"                                                                                                    |
|         2         | 90<br>(a little Small) |     2<br>(High)      |     0<br>(None)     | "Happy" (4), "Delighted" (2), "He looks happy because it looks like a dog's tail." And, "A little bit happy."                                                    |
|         3         |     210<br>(Large)     |    4<br>(Medium)     |     0<br>(None)     | "Fun", "Uplifted", "Normal", "I don't know, but she seemed kind of positive and calm.", "I hate it.", "Confused", "Puzzled, Retreating", "Bored"                 |
|         4         |    15-210<br>Random    |    2-6<br>Random     | 250-10000<br>Random | "Upset" (2), "Guilt", "Skepticism", "Nervous", "Suspicious behavior", "Thinking, Contemplation", "Timid".                                                        |
|         5         |     60<br>(Small)      |    4<br>(Medium)     |     0<br>(None)     | "Smile," "nose itchy," "Dazed", "Itchy, Impatient", "Scared (Same as 1).”, 'I can't...' 'Sad', 'Negative', 'I'm not sure.'                                       |
|         6         |     210<br>(Large)     | 3<br>(a little High) |    50<br>(Small)    | "Excited" (2) , "Irritated" (2), "Energetic", "Happy (Same as 2)", "Happy", "in a happy mood (In Japanese onomatopoeic word for "Rurun-Rurun".)", "Quite happy". |
|         7         |    120<br>(Medium)     | 6<br>(a little Low)  |   200<br>(Medium)   | "Irritable", "Restless", "Focused", "It's unnatural. I don't understand.", "Lost", "unsure", "unable to read emotions"                                           |
|         8         |     210<br>(Large)     |      8<br>(Low)      |    500<br>(High)    | "Wait and see", "Mechanical", "Lost", "Equanimity (Same as 4).", "It's unnatural. I don't understand (Same as 7).", "Calm", "unable to read emotions", "Settled" |





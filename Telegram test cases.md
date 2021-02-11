## Telegram mobile app test cases ##

| № |        Test case title       |                           Summary                          |                                                                                 Preconditions                                                                                 |                                                                                                                                                   Step actions                                                                                                                                                   |                                                                                                                                                  Actual result                                                                                                                                                  |
|---|:----------------------------:|:----------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| 1 | Sending a text message       | Checking the sending<br>a text message to <br>another user | 1. Open the Telegram app and sign in with <br>registered user.<br>2. The user's contact list includes other users Telegram.                                                   | 1. Select a user from your contact list.<br>2. Tap on the "Message..." field in the botton of the screen.<br>3. Type a text message in the "Message..." field.<br>4. Tap on the "Send" button.<br>5. Check the delivering message status.                                                                        | 1. The dialog screen is opened.<br>2. The keyboard is opened.<br>3. The typed text is displayed on the screen.<br>4. The message is sent.<br>5. The check mark is displayed under the sent message.                                                                                                             |
| 2 | Sending a multimedia message | Checking the sending a<br>multimedia message               | 1. Open the Telegram app and sign in with<br>registered user.<br>2. The user's contact list includes other users Telegram.<br>3. The user has multimedia files on his device. | 1. Select a user from your contact list.<br>2. Tap on the "Paperclip" icon in the botton of the screen.<br>3. Choose one or more multimedia files on the "Choosing file" screen.<br>4. Tap on the "Send files" button.<br>5. Check the delivering files status.                                                  | 1. The dialog screen is opened.<br>2. The file type selection screen is opened.<br>3. The chosen file and the "Send file" button are displayed.<br>4. The file is sent.<br>5. The check mark is displayed under the sent multimedia message.                                                                    |
| 3 | Receiving a message          | Checking the receiving a<br>message                        | 1. Download the Telegram app and sign up.<br>2. The message from another Telegram user is sent on the<br>user's Telegram account.                                             | 1. Recieve a message from another Telegram user.<br>2. Tap on the pop-up notification.<br>3. Read the message.                                                                                                                                                                                                   | 1. The pop-up notification about new message is received.<br>2. The dialog with the sender is opened in the Telegram app.<br>3. The information from message is received.                                                                                                                                       |
| 4 | Making a video call          | Checking the functionality of a <br>video call             | 1. Open the Telegram app and sign in with registered user.<br>2. The user's contact list includes other users Telegram                                                        | 1. Select a user from your contact list.<br>2. Go to the user's profile by clicking on his nickname or avatar.<br>3. Tap on the "Camera" icon.<br>4. Adjust the volume and microphone status.<br>5. Wait until the other person answers the video call.<br>6. Tap the end call button after the end of the call. | 1. The dialog screen is opened.<br>2. The user's profile is opened.<br>3. The notification about Telegram video call is sent to interlocutor.<br>4. The volume nd microphone status is changed according to user's task.<br>5. The video call is started.<br>6. Video contact with the interlocutor is cut off. |
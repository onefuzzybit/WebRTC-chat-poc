# WebRTC-chat-poc

A simple WebRTC program based on a tutorial i found on [tutorials-point](https://www.tutorialspoint.com/webrtc/index.htm)

## Starting the demo
1. clone this repository, and open in vscode
2. npm install
3. Ctrl+Shift+P => Tasks: Run Tasks => Start Chatroom
4. use 2 tabs to navigate to localhost:8080/index.html
5. place the tabs side by side (for comfort)
6. login on the left side using the name 'left'
7. login on the right side using the name 'right'   
![Image of side by side login](https://github.com/onefuzzybit/WebRTC-chat-poc/blob/main/assets/side-by-side-login.png?raw=true)
8. on the left side - use the 'call' form to call the right side   
![Image of side by side login](https://github.com/onefuzzybit/WebRTC-chat-poc/blob/main/assets/side-by-side-call.png?raw=true)
9. write input on the message input box and click 'send'   
![Image of side by side login](https://github.com/onefuzzybit/WebRTC-chat-poc/blob/main/assets/side-by-side-send.png?raw=true)
10. see your message on the other side:
![Image of side by side login](https://github.com/onefuzzybit/WebRTC-chat-poc/blob/main/assets/side-by-side-see-output.png?raw=true)


## Troubleshooting
If you cannot run in vscode, or the 'run tasks' command doesn't work for you for some reason, you can manually run 2 commands:
1. `npm start` - will start the signalling server
2. `npx http-server` - in the root folder of the code - will run a web server that can server the index.html file.

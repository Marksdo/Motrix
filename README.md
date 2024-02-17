# 🎠 Motrix - macOS native chatGPT client

Download [the latest release from macOS appstore](https://apps.apple.com/us/app/id6447776319)

## Features
- support local LLM proxy litellm
- You must have an GPT API Key to run Motrix App
- Connect chatGPT API or GPT Proxy service (Custom host)
- Group chat support
- Auto retry
- Regenerate response
- Query Image By Enter ! in input box
- Quick Prompt Template popup selector
- Chat nodes can be organize like tree (Drag & Drop)
- Global quick open switch back to chat
- Custom chat nodes show on Menubar 
- Markdown render conversations
- Save favorites chat and query later
- AI visible icon point out how many contextual message AI can read
- Search conversation by keywords
- Embed 3 themes with Light/Dark support
- Embed tiny markdown editor to collect things
- Embed online code playground
- Support change conversation font-size
- Support change model parameters any time
- Stay on top switch
- Multilanguage support

V1.9.2
---
- Add feature to backup all datas and restore back in preferences.  
- Add feature to duplicate message to another chat node  
- Add memo chat mode to only save something and not send ai server  
- Add tmp send message as group chat message by start new chat with format '@node1;node2;node5 newline translate text'  
- Add quick tmp group chat from left tree node's context menu  
- Add feature to lock context to row, let conversation always send from locked context row  
- Add double tap to edit timer tiny pop chat window to edtior mode  
- Add group chat parallel thread options in slide bar, it use to reduce parallel request to api cause server response issue  
- Add edit timer pop options direct inside pop chat window  
- Add shortcut to open any chat node with float window  
- Fixed quick window theme style not match  
- Fixed stream mode can't read data from open source project litellm with proxy mode
- [V1.9.2-Uni](https://download.marksdo.com/apps/Motrix/V1.9.2/Motrix.dmg) 



V1.9.1
---
- Add double tap to edit timer tiny pop chat window to edtior mode
- Add edit timer pop options direct inside pop chat window
- Add shortcut to open any chat node with float window
- Fixed quick window theme style not match
- Fixed stream mode can't read data from open source project litellm with proxy mode
- [V1.9.1-Uni](https://download.marksdo.com/apps/Motrix/V1.9.1/Motrix.zip) 

V1.9.0
---
- Add support llm/gpt proxy deploy local (litellm) http://127.0.0.1:8000 as host to support most open source llm/gpt chat server
- Add clone feature for chat tree node in right context menu
- Add batch setup nodes model parameters feature (select multi-nodes from tree then use context menu -> batch setup)
- Fixed system instructions description can't collapse issue
- [73.6 MB](https://download.marksdo.com/apps/Motrix/V1.9.0/Motrix.zip) 
![image](/images/V190.webp)

V1.8.9
---
- Add shortcut to switch to next tree chat node (Use to combine with other system batch shortcut apps)
- Add snapshot in chat content right context menu.
- Schedule popup AI query result window can save to full result image to clipboard
- Chat content row toolbar removed. Use right context menu as replacement
- Fixed batch share chat content to image layout issue
- Fixed crash on startup macOS 11
- Download universal edtiton [73.5 MB](https://download.marksdo.com/apps/Motrix/V1.8.9/Motrix.zip) 


V1.8.7
--- 
- Add model key config. you can config connect model key when new model release.
- Add batch select chat rows delete feature
- Add option to disable auto scroll to chat list bottom
- Add appearance config to change ui font size
- Add shortcut ⌘+(+-) to quick change chat content size
- Add fixed input box height option in option slider
- Left navigation bar size can be more small size
- New chat node will use last selected chat node ai parameters
- Fixed schedule popup custom ai question still popup when system is sleep
- Fixed markdown render option can't toggle on settings
- Fixed shortcuts app motrix intent issue

V1.8.5
---
- Added support new GPT3.5 & GPT4 16K model  
- Added support custom timer popup window default width (Use for long response daily ai tips)  
- Fixed stream mode some case display issue  
- Fixed the tiny popup timer window display bugs  
- Fixed macOS11.0 new node stuck issue

V1.8.4
---
- Add new chat guide page. You can select an predefined AI Role to start chat.
- Bug fixed and Performance improvements.

V1.8.3
---
- Add grid view in Motrix Quick service chat node selector
- Add option to enable/disable unread message in left tree node
- Add option to disable typing autoscroll
- Fixed can't reactive to front by click dock bar app icon
- Fixed some multi-language do not translate
- Fixed speech mode sometime crash issue


V1.8.2
---
- Add Shortcuts App support (macOS 13.0+)  Query AI response then embed in to your self auto workflow. You can view how to use inside app's preferences
- Motrix quick service now can select tiny window to show ai response content 
- Fixed Motrix service can't show on browser or other text app


V1.8.1
---
- Fixed global search sometime can't list data
- Fixed pro plans still limit some features
- Fixed message body height not fit issue

V1.8
---
- Add daily timer to auto query ai chat node for popup inspirational or motivational tips, Or you can use it to daily auto popup an coding tips, Language practise. (Double tap on user question row)  
- Add daily timer can direct invoke from Motrix menubar's contextmenu  
- Add global shortcut CMD+SHIFT+F quick switch to global search favorites  
- Fix fix fix scroll issues  
- Fix pop template selector sometimes can't insert text  
- Stream mode performance improvements


V1.7 Features
---
- Add float win mode, you can make an chat windown to an new tiny floating panel
- Add support drag text to chat window any area to send message
- Add show layout switch on main toolbar option & support custom layout restore icon
- Add Motrix quick system service, When in other editor app select any text select Motrix quick will  popup chat nodes selector and send selected text to the chat system
- Add right mouse context menu on message for quick copy & fav & edit
- Fix scrollview stable issue
- Fix markdown newline bug

V1.5~1.6 Features
---
- Add stream mode to get response tokens one by one
- Add message embed edit by double tap the message row
- Add appearance config in settings for some UI custom
- Add 3 new themes with Light & Dark support
- Add layout save & restore features (include current theme & lightDark & font size & auto options ...) 
- Add Typing animation option
- Add os text service, call Motrix's api in all other system texteditor
- Fixed & Tested Mortix is compatible with macOS 11.0, 12.0 devices
- Bug fixed and Performance improvements

V1.4 Features
---
- Support search in all conversations
- Support batch select mode. select chat messages to share or export
- Support show favorites in all conversations (Inside search menu)
- Custom each node max tokens (You must know how these work, like context message,it can effect ai know how much of the the contextual)
- Custom node default enter mode
- Bug fixed and Performance improvements

V1.1~V1.3 Features
---
- Speech mode: you can use microphone to record text. App will translate to text and keep the audio track.
- Voice speak content: Single click user or bot avatar.
- Group chat mode: you can set parent node and add some child nodes (Must use system instructions to init ai role & it's role), then send message in parent node, All childs will give response in current conversation.
- Auto clipboard: auto copy content to clipboard when response in
- Auto speech: auto speak response
- Auto mask: auto mask ai response. This is mainly for users who want to practice dictation of various languages.

V1.0 Features
---
- Embed markdown editor
- Freely group chat node with tree style (support drag and drop)
- 3 Themes with light/dark color support 
- Code block color render
- Save any conversation for later review or query
- Conversation save in local, so it can later view offline
- Custom prompt template and quick popup with "/"


Screenshots

![screenshot](images/screenshot.webp)

![screenshot1](images/screenshot1.webp)

![screenshot2](images/screenshot2.webp)

![screenshot3](images/screenshot3.webp)

![screenshot4](images/screenshot4.webp)

![screenshot5](images/screenshot5.webp)

![screenshot6](images/screenshot6.webp)

![screenshot7](images/screenshot7.webp)

![screenshot8](images/screenshot8.webp)

![screenshot9](images/screenshot9.webp)

![screenshot10](images/screenshot10.webp)

![screenshot11](images/screenshot11.webp)

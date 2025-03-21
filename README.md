# SRT-Hunter
SRT Automated Booking Agent (v1.3.4)
## Features
- GUI-based interface
- SRT automatic login and booking automation
- KakaoPay automatic payment integration
- Multi-passenger reservation support (1-4 people)
- Pause and reset functionality
- Display of payment completion details
## UI
![ui](https://github.com/user-attachments/assets/30db9ec0-493e-4cc2-852b-4ec1fe2ff06a)
## Download
- Download: [Latest Release](https://github.com/root39293/srt-hunter/releases/latest)
- Run on your own PC
~~~bash
git clone https://github.com/root39293/srt-hunter.git
cd srt-hunter
poetry install
poetry run python main.py
~~~
## Notice
- For personal use only
- Recommended refresh interval of 0.05 seconds or higher
- Chrome browser required
## Change Log
### v1.3.4
- Fixed build script bugs
### v1.3.3
- Added multi-passenger reservation feature (1-4 people)
- Improved login information management method (text file saving excluding password)
- Changed seat type selection to radio buttons
- Added pause and reset buttons
- Improved user interface
### v1.2.1
- Added login information saving feature
### v1.1.1
- Improved payment completion detection logic
- Added payment details (amount, approval date/time) display feature
- Enhanced payment completion page stability
## License
MIT License

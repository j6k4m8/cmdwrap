# command wrappers

# Setup
Clone this repo and rename the settings-file. Install requirements.
```
git clone git@github.com:j6k4m8/cmdwrap.git
cd cmdwrap
mv demo-settings.py settings.py
pip install -r requirements
```
Now edit `settings.py` with your own account data. Your account access token is [here](https://www.pushbullet.com/#settings/account). Device identifiers can be found by navigating to [the Pushbullet devices page](https://www.pushbullet.com/#devices) and clicking on your phone: The url of that page is then:
```
https://www.pushbullet.com/#devices/XXXXXzzzzzzzzzzz
```
The `XXXXX` is your `user_iden`, the full `X` and `z` string is your `device_iden`.

# Usage
Simply preface a command with `abw` to turn your anybar red until your command finishes (it'll turn blue).

Preface a command with `pbw` (e.g. `pbw rm bigfile`) to wrap it in pybullet: You'll get a text message once it finishes.

# Contributing
Pull-requests welcome! Bug reports (via [the Issues page](https://github.com/j6k4m8/cmdwrap/issues)) also welcome.

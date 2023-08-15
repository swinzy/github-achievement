# LBP Website Booking System Test Playground[^1]
## Configure Environment
Prerequisite:
- Python >= 3.8.x
- Node.js >= 18.16-LTS
- Flask >= 2.3.2

### Install Node.js
**Linux**: <br>
Install package `nodejs`

**Windows**: <br>
Download from <a href="https://nodejs.org/en">official website</a> or winget (`winget install OpenJS.NodeJS.LTS`)

### Install Flask[^2]
#### Create Virtual Environment
**Linux**:<br>
Under `/lbp-booking/lbp-booking`, execute:
```
$ python -m venv .venv
$ . .venv/bin/activate
```

**Windows**:<br>
Under `\lbp-booking\lbp-booking`, execute:
```
> py -3 -m venv .venv
> .venv\Scripts\activate
```

#### Use Freeze to Install Shared Dependencies[^3]
**¡Make sure your virtual environment in activated!**<br>
PS: Check if `(.venv)` is displayed before your prompt

**Linux**:<br>
`./install_req.sh`

**Windows**:<br>
`pip install -r requirements.txt`

[^1]: *Written by Stephen Zhang 15 Aug 2023*
[^2]: [Flask installation documentation](https://flask.palletsprojects.com/en/2.3.x/installation/)
[^3]: [pip freeze documentation](https://pip.pypa.io/en/stable/cli/pip_freeze/)

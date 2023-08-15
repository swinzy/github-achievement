# LBP Website Booking System Test Playground[^4]
## Configure Environment
Prerequisite:
- Python >= 3.8.x
- Node.js >= 18.16-LTS
- Next.js >= 9.5.1
- Flask >= 2.3.2

### Install Node.js
**Windows**: <br>
Download from <a href="https://nodejs.org/en">official website</a> or winget (`winget install OpenJS.NodeJS.LTS`)
**Linux**: <br>
Install package `nodejs`

### Install React/Next.js[^1]
`npm install next@latest react@latest react-dom@latest`

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

[^1]: [Next.js getting started documentation](https://nextjs.org/docs/getting-started/installation)
[^2]: [Flask installation documentation](https://flask.palletsprojects.com/en/2.3.x/installation/)
[^3]: [pip freeze documentation](https://pip.pypa.io/en/stable/cli/pip_freeze/)
[^4]: *Written by Stephen Zhang 15 Aug 2023*

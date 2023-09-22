# Pomodoro
Pomodoro is a pomodoro timer and a desktop application.

## Screenshot
![Pomodoro](https://raw.githubusercontent.com/ricmsd/pomodoro/main/docs/screenshot.png)

## How to use
Operation is simple.
- The timer starts when you start the application.
- The timer stops after 30 minutes.
- Clicking on the screen restarts the timer from zero.

## How to build
### requirements
- Node.js v18.17.1

### Trial run
Clone the repository and run the npm command.

    git clone https://github.com/ricmsd/pomodoro.git
    cd pomodoro
    npm install
    npm run start

### Generate installer
Running `npm run make` instead of `npm run start` will generate an installer (.exe).

    git clone https://github.com/ricmsd/pomodoro.git
    cd pomodoro
    npm install
    npm run make

The installer is located in the `podomoro` folder `out/make/.../pomodoro-X.X.X Setup.exe` (where `X.X.X` is the version).

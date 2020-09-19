# Discord Token Generate and Check

Generator:
https://github.com/Weberowsky/Discord-tokens-generator

Checker:
https://github.com/Lemons1337/Discord-Token-Checker

Discord login with token:

1- First come login place on discord. Press CTRL+Shift+i and paste this code in console:

function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 2500);
}

after:
login('your token')



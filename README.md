# OCRWatch

Using OCR to track match stats & team performance in Overwatch 2  
Fancier continuation of https://github.com/InventivetalentDev/ocrwatch

## How it works
While this app is running, it listens for key presses of Tab and takes a screenshot of the scoreboard if it's held for more than 0.5 seconds.
It then applies OCR on that screen, including mode and map info, which hero you're playing and stats of you and other players in your game (kills, deaths, healing, etc.) and saves that data.



## Usage
```
git clone https://github.com/InventivetalentDev/ocrwatch2.git
cd ocrwatch2
```
```
copy config.example.json config.json
npm install
npm run start
```

### windows 11
```
update options
System > Display > Graphics
add an app
select desktop app
click browse
add the electron binary
add C:\projects\ocrwatch2\node_modules\electron\dist
click options on new program
select high performance
```

![](https://yeleha.co/8uD3zIdt)

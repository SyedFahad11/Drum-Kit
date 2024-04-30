# Drum Kit using JavaScript Document Object Model (DOM) and Event Listeners

This project is a simple drum kit implemented using JavaScript's Document Object Model (DOM) and event listeners. Users can play different drum sounds by either clicking on the corresponding drum buttons or by pressing specific keys on their keyboard.
<br>
Live Deployment Link <a href="https://syedfahad11.github.io/Drum-kit/"> Click Here</a>
## How it Works

The drum kit consists of buttons representing different drums, and each button corresponds to a specific drum sound. Users can trigger a drum sound by either clicking on the corresponding button or by pressing the associated key on their keyboard.

## Functionality

The `makesound` function is responsible for playing the drum sounds based on the input key:

```javascript
function makesound(key) {
  switch (key) {
    case "w":
      var crash = new Audio("./sounds/crash.mp3");
      crash.play();
      break;
    case "a":
      var kick = new Audio("./sounds/kick-bass.mp3");
      kick.play();
      break;
    case "s":
      var snare = new Audio("./sounds/snare.mp3");
      snare.play();
      break;
    case "d":
      var tom1 = new Audio("./sounds/tom-1.mp3");
      tom1.play();
      break;
    case "j":
      var tom2 = new Audio("./sounds/tom-2.mp3");
      tom2.play();
      break;
    case "k":
      var tom3 = new Audio("./sounds/tom-3.mp3");
      tom3.play();
      break;
    case "l":
      var tom4 = new Audio("./sounds/tom-4.mp3");
      tom4.play();
      break;
    default:
      console.log(key);
  }
}
```

## Usage

To play the drum sounds:

1. Open the `index.html` file in your web browser.
2. Click on the drum buttons to play the corresponding drum sounds.
3. Alternatively, use the following keys on your keyboard to play the respective drum sounds:
   - "w" for crash
   - "a" for kick bass
   - "s" for snare
   - "d" for tom 1
   - "j" for tom 2
   - "k" for tom 3
   - "l" for tom 4

## How to Run

To run the drum kit locally:

1. Clone the repository to your local machine.
2. Open the `index.html` file in your web browser.
   
![Screenshot (314)](https://user-images.githubusercontent.com/106341416/170878446-035c7351-2ff4-47c4-8425-093c1795616b.png)

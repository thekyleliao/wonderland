# Chest Sixteen

### Started With:
- Toy Dog Guitar
- Lysol Spray
- Liquid Nails
- Gourd
- Command Hooks

### Team Members:
- @thekyleliao
- Valerii Ahin
- Vincent
- William

### Trade Record:
- No trades.

## End Result
![Dog](https://i.imgur.com/GVZJr65.jpeg)
![Arduino](https://i.imgur.com/5U5JP7y.jpeg)
![Kite](https://i.imgur.com/EFirqVG.jpeg)

### Ended With:
- Chinese Speaking Dog Guitar
- Home Made Kite
- Terminal Game

### Project Summary
- We built a Gemini API enabled Wonderland themed game where you roleplay as Alice's shrinking potion, a home made kite using a table cloth, and a "Chinese" speaking Dog Guitar using an Arduino and some buttons from the Dog.

### How did the items in your box inspire you?
*The Dog Guitar pired me to build a kite*

### What items did you use?
- *All of them? Some of them? List out which ones!*
- All of them, not all successfully!

### Code Links
[Game](https://github.com/thekyleliao/wonderland_gemini)
[Dog!]
```
#define BTN1 2
#define BTN2 3
#define BTN3 4
void setup() {
  // put your setup code here, to run once:
  pinMode(BTN1, INPUT_PULLUP);
  pinMode(BTN2, INPUT_PULLUP);
  pinMode(BTN3, INPUT_PULLUP);
  pinMode(5, OUTPUT);
  Serial.begin(9600);
}

void loop() {
  // put your main code here, to run repeatedly:
  if (digitalRead(BTN1) == LOW) {
    Serial.println("我");
    digitalWrite(5, HIGH); // turn the LED on
    delay(1000);           // wait for 1 second
    digitalWrite(5, LOW);  // turn the LED off
    delay(1000);
    }
  if (digitalRead(BTN2) == LOW) {
    Serial.println("爱");
    digitalWrite(5, HIGH); // turn the LED on
    delay(1000);           // wait for 1 second
    digitalWrite(5, LOW);  // turn the LED off
    delay(1000);
  }
  if (digitalRead(BTN3) == LOW){
    Serial.println("你");
    digitalWrite(5, HIGH); // turn the LED on
    delay(1000);           // wait for 1 second
    digitalWrite(5, LOW);  // turn the LED off
    delay(1000);
  }
}
```

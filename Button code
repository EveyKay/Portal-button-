#include <Keyboard.h>
#include <Bounce2.h>
 
#define BUTTON_PIN 3

 int ledState = LOW;
 
Bounce2::Button button = Bounce2::Button();
 
void setup() {
  // Set buttons
  button.attach(BUTTON_PIN, INPUT_PULLUP);
  button.interval(5);
  button.setPressedState(LOW);
 
  // Set LEDs
  pinMode(LED_BUILTIN, OUTPUT);
  digitalWrite(LED_BUILTIN, ledState);
 
  // HID Keyboard
  Keyboard.begin();
}
 // Presses shortcut keys, control+shift+p+l , feel free to change if it is already a shortcut on your computer
void loop() {
  button.update();
  if (button.pressed()) {
    ledState = !ledState;
    digitalWrite(LED_BUILTIN, ledState);
    Keyboard.press(KEY_LEFT_CTRL);
    Keyboard.press(KEY_LEFT_SHIFT): 
    Keyboard.press('p'); 
    Keyboard.press(KEY_LEFT_ALT);
    delay(50);
    Keyboard.releaseALL();

  }
}

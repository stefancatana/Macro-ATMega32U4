#include <HID.h>
#include <Keyboard.h>

// connected 
const int switch_pin1        = 2;
const int switch_pin2        = 3;
const int switch_pin3        = 10;
const int switch_pin4        = 5;
const int switch_pin5        = 6;
const int switch_pin6        = 7;
const int switch_pin7        = 8;
const int switch_pin8        = 9;

int button_state            = 0;
int previous_button_state   = HIGH;
long last_debounce_time     = 0;
const long debounce_delay   = 50;

void setup() 
{
  pinMode(switch_pin1,INPUT_PULLUP); 
  digitalWrite(switch_pin1, HIGH);

  pinMode(switch_pin2,INPUT_PULLUP); 
  digitalWrite(switch_pin2, HIGH);
  
  pinMode(switch_pin3,INPUT_PULLUP); 
  digitalWrite(switch_pin3, HIGH);

  pinMode(switch_pin4,INPUT_PULLUP); 
  digitalWrite(switch_pin4, HIGH);
  pinMode(switch_pin5,INPUT_PULLUP); 
  digitalWrite(switch_pin5, HIGH);

  pinMode(switch_pin6,INPUT_PULLUP); 
  digitalWrite(switch_pin6, HIGH);

  pinMode(switch_pin7,INPUT_PULLUP); 
  digitalWrite(switch_pin7, HIGH);

  pinMode(switch_pin8,INPUT_PULLUP); 
  digitalWrite(switch_pin8, HIGH);
  
  Keyboard.begin();
}


void loop() 
{
  button_state = digitalRead(switch_pin1);
  if ((button_state != previous_button_state) && (button_state == HIGH)) 
  {
    if ((millis() - last_debounce_time) > debounce_delay) 
    {
      Keyboard.press(KEY_F13);
      delay(100);
      Keyboard.releaseAll(); 
      last_debounce_time = millis();
    }
  }
   previous_button_state = button_state;

  button_state = digitalRead(switch_pin2);
  if ((button_state != previous_button_state) && (button_state == HIGH)) 
  {
    if ((millis() - last_debounce_time) > debounce_delay) 
    {
      Keyboard.press(KEY_F14);
      delay(100);
      Keyboard.releaseAll(); 
      last_debounce_time = millis();
    }
  }
  previous_button_state = button_state;

  button_state = digitalRead(switch_pin3);
  if ((button_state != previous_button_state) && (button_state == HIGH)) 
  {
    if ((millis() - last_debounce_time) > debounce_delay) 
    {
       Keyboard.press(KEY_F15);
      delay(100);
      Keyboard.releaseAll(); 
      last_debounce_time = millis();
    }
  }
  previous_button_state = button_state;

  button_state = digitalRead(switch_pin4);
  if ((button_state != previous_button_state) && (button_state == HIGH)) 
  {
    if ((millis() - last_debounce_time) > debounce_delay) 
    {
      Keyboard.press(KEY_F16);
      delay(100);
      Keyboard.releaseAll(); 
      last_debounce_time = millis();
    }
  }
  previous_button_state = button_state;

  button_state = digitalRead(switch_pin5);
  if ((button_state != previous_button_state) && (button_state == HIGH)) 
  {
    if ((millis() - last_debounce_time) > debounce_delay) 
    {
      Keyboard.press(KEY_F17);
      delay(100);
      Keyboard.releaseAll(); 
      last_debounce_time = millis();
    }
  }
  previous_button_state = button_state;

  button_state = digitalRead(switch_pin6);
  if ((button_state != previous_button_state) && (button_state == HIGH)) 
  {
    if ((millis() - last_debounce_time) > debounce_delay) 
    {
      Keyboard.press(KEY_F18);
      delay(100);
      Keyboard.releaseAll(); 
      last_debounce_time = millis();
    }
  }
  previous_button_state = button_state;

  button_state = digitalRead(switch_pin7);
  if ((button_state != previous_button_state) && (button_state == HIGH)) 
  {
    if ((millis() - last_debounce_time) > debounce_delay) 
    {
      Keyboard.press(KEY_F19);
      delay(100);
      Keyboard.releaseAll(); 
      last_debounce_time = millis();
      last_debounce_time = millis();
    }
  }
  previous_button_state = button_state;

  button_state = digitalRead(switch_pin8);
  if ((button_state != previous_button_state) && (button_state == HIGH)) 
  {
    if ((millis() - last_debounce_time) > debounce_delay) 
    {
      Keyboard.press(KEY_F20);
      delay(100);
      Keyboard.releaseAll(); 
      last_debounce_time = millis();
    }
  }
  previous_button_state = button_state;
}

// Blue LEDs on pins 13–8
int blueLeds[] = {13, 12, 11, 10, 9, 8};
// Red LEDs on pins 7–2
int redLeds[]  = {7, 6, 5, 4, 3, 2};

void setup() {
  for (int i = 0; i < 6; i++) {
    pinMode(blueLeds[i], OUTPUT);
    pinMode(redLeds[i], OUTPUT);
  }
}

void loop() {
  // Flash blue rapidly
  for (int j = 0; j < 5; j++) {
    for (int i = 0; i < 6; i++) digitalWrite(blueLeds[i], HIGH);
    delay(80);
    for (int i = 0; i < 6; i++) digitalWrite(blueLeds[i], LOW);
    delay(80);
  }

  // Flash red rapidly
  for (int j = 0; j < 5; j++) {
    for (int i = 0; i < 6; i++) digitalWrite(redLeds[i], HIGH);
    delay(80);
    for (int i = 0; i < 6; i++) digitalWrite(redLeds[i], LOW);
    delay(80);
  }
}

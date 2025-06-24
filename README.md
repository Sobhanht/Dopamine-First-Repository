# Dopamine-First-Repository
#First-repository
#first edit
# blink by while
const int ledPin = LED_BUILTIN;
int ledState = LOW;
int a = 5;
void setup() {
  // put your setup code here, to run once:
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  
 while (a < 6)
 {
  digitalWrite(LED_BUILTIN, 1);
  delay(1000);
  digitalWrite(LED_BUILTIN, 0);
  delay(1000);
}
}




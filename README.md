# switch2
ㅡㅡ
void setup() {
  // put your setup code here, to run once: 
  pinMode(8, OUTPUT);
  pinMode(5, INPUT_PULLUP);
}

void loop() {
  if(digitalRead(5)==0){
    digitalWrite(8, HIGH);
  }else{
    digitalWrite(8, LOW);
  }
}

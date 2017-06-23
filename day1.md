```
void setup() {
  pinMode(11,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(9,OUTPUT);
}

void loop() {
  digitalWrite(11,HIGH);
  delay(500);
  digitalWrite(10,HIGH);
  delay(500);
  digitalWrite(9,HIGH);
  delay(500);
  digitalWrite(11,LOW);
  digitalWrite(10,LOW);
  digitalWrite(9,LOW);
  delay(500);
   digitalWrite(11,HIGH);
  digitalWrite(10,HIGH);
  digitalWrite(9,HIGH);
  delay(500);
  digitalWrite(11,LOW);
  delay(500);
  digitalWrite(10,LOW);
  delay(500);
  digitalWrite(9,LOW);
  delay(2000);
}
```

!["照片"](https://github.com/superliran/Homework-of-Arduino/blob/master/images/IMG_20170623_151814.jpg)


```

void setup() {

  pinMode(11, OUTPUT); 

  pinMode(3, OUTPUT);

}



void loop() {

  analogWrite(11,analogRead(A3)/4);

  analogWrite(3,255-analogRead(A3)/4);

}

```



![day2](https://github.com/superliran/Homework-of-Arduino/blob/master/images/IMG_20170622_171634.jpg)day2

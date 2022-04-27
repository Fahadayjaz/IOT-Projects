# IOT-Projects
int buzzer =6;
int led =3;

{
pinMode(6,OUTPUT);
pinMode(3,OUTPUT);
}

{
tone(buzzer,3000);
noTone(buzzer);
digitalWrite(3,HIGH);
delay(500);
digitalWrite(3,LOW);
delay(500);
}

int pushbutton = 8;
int LED = 2;

void setup()
{
pinMode(pushbutton, INPUT);
pinMode(LED, OUTPUT);
}

void loop()
  {
    int status = digitalRead(pushbutton);
      if (status == 1)
        {
          digitalWrite(LED, HIGH);
        }
      else
        {
          digitalWrite(LED,LOW);
        }
}

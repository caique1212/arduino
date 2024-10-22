# arduino
trabalho em arduino


![image](https://github.com/user-attachments/assets/ccec670d-78af-4e26-b694-e4b6ea3105de)





// C++ code
//
void setup()
{
  pinMode(10, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(9, OUTPUT);
}

void loop()
{
  digitalWrite(10, HIGH);
  digitalWrite(4, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(4, LOW);
  digitalWrite(2, HIGH);
  delay(5000); // Wait for 3000 millisecond(s)
  digitalWrite(2, LOW);
  digitalWrite(3, HIGH);
  delay(2000); // Wait for 1000 millisecond(s)
  digitalWrite(10, LOW);
  digitalWrite(4, HIGH);
  digitalWrite(3, LOW);
  digitalWrite(8, HIGH);
  delay(5000); // Wait for 3000 millisecond(s)
  digitalWrite(9, HIGH);
  delay(2000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  digitalWrite(9, LOW);
}

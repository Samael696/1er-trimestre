# 1er-trimestre
int valuepuls = 0, pinpuls = 4; // VARIABLE Y PIN DEL PULSADOR 
int led3 = 3; // PINS DE CONEXIÓN DEL LED

void setup() {
  
  //CONFIGURACIÓN DE LOS LEDS
  
pinMode (led3, OUTPUT);

  //CONFIGURACIÓN DEL PULSADOR
  pinMode (pinpuls, INPUT);
}

void loop() {
  
  // SI PULSAMOS EL PULSADOR SE ENCENDERÁ EL LED3
  
valuepuls = digitalRead (pinpuls); 
  if (valuepuls == HIGH) // PULSADOR NO PULSADO
  {
    digitalWrite (led3, LOW); // LED3 = OFF
  }
  else
  {
    digitalWrite (led3, HIGH); // LED3 = ON
  }

}

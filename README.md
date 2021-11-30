# 1er-trimestre

```c++
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
```

![imagen](https://user-images.githubusercontent.com/90753326/133392921-7047aec6-2fe8-4f83-bd3b-39fd3ec56df0.png)

https://github.com/d-prieto

Bienevenidos al 1er cuatrimestre

-me llamo Andree

-me gusta el fútbol

-mi idolo es [maradona](https://es.wikipedia.org/wiki/Diego_Maradona)

-soy de Perú

-me interesa aprender programacion en arduino

⛈️⛈️⛈️⛈️⛈️⛈️⛈️⛈️⛈️⛈️


[Arquitectura de ordenadores](https://github.com/Samael696/1er-trimestre/blob/main/Arquitectura%20de%20ordenadores.MD)

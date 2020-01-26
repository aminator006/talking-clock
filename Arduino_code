#include <SPI.h>

#include <Wire.h>
#include "RTClib.h"
#include "Talkie.h"
#include "Vocab_US_Large.h"

RTC_DS1307 rtc;
Talkie voice;




void setup() {
  // put your setup code here, to run once:


  Serial.begin(9600);
 if (! rtc.begin()) {
    Serial.println("Couldn't find RTC");
    while (1);
  }

  if (! rtc.isrunning()) {
    Serial.println("RTC is NOT running!");
    // following line sets the RTC to the date & time this sketch was compiled
   rtc.adjust(DateTime(F(__DATE__), F(__TIME__)));
  
  }
}

void loop() {
  DateTime now = rtc.now();
  int v=0;
  int h=now.hour();
  int m=now.minute();
  int s=now.second();
  
  if (h>11){
    v=1;
  }
 if (h>12) {
  h=h-12;
 }
   
   Serial.print(h);
 

   Serial.print(":");
   Serial.print(m);
   Serial.print(":");
   Serial.print(s);
   Serial.println();
  
   
    voice.say(sp3_THE);
    voice.say(sp3_TIME);
    voice.say(sp3_IS);

   if (h==1){
    voice.say(sp3_ONE);
   }
   if (h==2){
    voice.say(sp3_TWO);
   }
   if (h==3){
    voice.say(sp3_THREE);
   }
   if (h==4){
    voice.say(sp3_FOUR);
   }
   if (h==5){
    voice.say(sp3_FIVE);
   }
   if (h==6){
    voice.say(sp3_SIX);
   }
   if (h==7){
    voice.say(sp3_SEVEN);
   }
   if (h==8){
    voice.say(sp3_EIGHT);
   }
   if (h==9){
    voice.say(sp3_NINE);
   }
   if (h==10){
    voice.say(sp3_TEN);
   }
   if (h==11){
    voice.say(sp3_ELEVEN);
   }
   if (h==12){
    voice.say(sp3_TWELVE);
   }
  if (m==0){
  voice.say (sp3_OCLOCK);
}
if (m==1){
 voice.say (sp3_ZERO);
 voice.say (sp3_ONE);
}
if (m==2){
  voice.say (sp3_ZERO);
  voice.say (sp3_TWO);
}
if (m==3){
  voice.say (sp3_ZERO);
  voice.say (sp3_THREE);
}
if (m==4){
  voice.say (sp3_ZERO);
  voice.say (sp3_FOUR);
}
if (m==5){
  voice.say (sp3_ZERO);
  voice.say (sp3_FIVE);
}
if (m==6){
  voice.say (sp3_ZERO);
  voice.say (sp3_SIX);
}
if (m==7){
  voice.say (sp3_ZERO);
  voice.say (sp3_SEVEN);
}
if (m==8){
  voice.say (sp3_ZERO);
  voice.say (sp3_EIGHT);
}
if (m==9){
  voice.say (sp3_ZERO);
  voice.say (sp3_NINE);
}
if (m==10){
 
  voice.say (sp3_TEN);
}
if (m==11){
 
  voice.say (sp3_ELEVEN);
}
if (m==12){
 
  voice.say (sp3_TWELVE);
}
if (m==13){
 
  voice.say (sp3_THIRTEEN);
}
if (m==14){
 
  voice.say (sp3_FOURTEEN);
}
if (m==15){
 
  voice.say (sp3_FIFTEEN);
}
if (m==16){
 
  voice.say (sp3_SIXTEEN);
}
if (m==17){
 
  voice.say (sp3_SEVENTEEN);
}
if (m==18){
 
  voice.say (sp3_EIGHTEEN);
}
if (m==19){
 
  voice.say (sp3_NINETEEN);
}
if (m==20){
 
  voice.say (sp3_TWENTY);
}

if (m==21){
   voice.say (sp3_TWENTY);
   voice.say (sp3_ONE);
}
if (m==22){
   voice.say (sp3_TWENTY);
   voice.say (sp3_TWO);
}
if (m==23){
   voice.say (sp3_TWENTY);
   voice.say (sp3_THREE);
}
if (m==24){
   voice.say (sp3_TWENTY);
   voice.say (sp3_FOUR);
}
if (m==25){
   voice.say (sp3_TWENTY);
   voice.say (sp3_FIVE);
}
if (m==26){
   voice.say (sp3_TWENTY);
   voice.say (sp3_SIX);
}
if (m==27){
   voice.say (sp3_TWENTY);
   voice.say (sp3_SEVEN);
}
if (m==28){
   voice.say (sp3_TWENTY);
   voice.say (sp3_EIGHT);
}
if (m==29){
   voice.say (sp3_TWENTY);
   voice.say (sp3_NINE);
}
if (m==30){
 
  voice.say (sp3_THIRTY);
}

if (m==31){
   voice.say (sp3_THIRTY);
   voice.say (sp3_ONE);
}
if (m==32){
   voice.say (sp3_THIRTY);
   voice.say (sp3_TWO);
}
if (m==33){
   voice.say (sp3_THIRTY);
   voice.say (sp3_THREE);
}
if (m==34){
   voice.say (sp3_THIRTY);
   voice.say (sp3_FOUR);
}
if (m==35){
   voice.say (sp3_THIRTY);
   voice.say (sp3_FIVE);
}
if (m==36){
   voice.say (sp3_THIRTY);
   voice.say (sp3_SIX);
}
if (m==37){
   voice.say (sp3_THIRTY);
   voice.say (sp3_SEVEN);
}
if (m==38){
   voice.say (sp3_THIRTY);
   voice.say (sp3_EIGHT);
}
if (m==39){
   voice.say (sp3_THIRTY);
   voice.say (sp3_NINE);
}
if (m==40){
 
  voice.say (sp3_FOURTY);
}

if (m==41){
   voice.say (sp3_FOURTY);
   voice.say (sp3_ONE);
}
if (m==42){
   voice.say (sp3_FOURTY);
   voice.say (sp3_TWO);
}
if (m==43){
   voice.say (sp3_FOURTY);
   voice.say (sp3_THREE);
}
if (m==44){
   voice.say (sp3_FOURTY);
   voice.say (sp3_FOUR);
}
if (m==45){
   voice.say (sp3_FOURTY);
   voice.say (sp3_FIVE);
}
if (m==46){
   voice.say (sp3_FOURTY);
   voice.say (sp3_SIX);
}
if (m==47){
   voice.say (sp3_FOURTY);
   voice.say (sp3_SEVEN);
}
if (m==48){
   voice.say (sp3_FOURTY);
   voice.say (sp3_EIGHT);
}
if (m==49){
 voice.say (sp3_FOURTY);
   voice.say (sp3_NINE);
}
if (m==50){
 
  voice.say (sp3_FIFTY);
}

if (m==51){
   voice.say (sp3_FIFTY);
   voice.say (sp3_ONE);
}
if (m==52){
   voice.say (sp3_FIFTY);
   voice.say (sp3_TWO);
}
if (m==53){
   voice.say (sp3_FIFTY);
   voice.say (sp3_THREE);
}
if (m==54){
   voice.say (sp3_FIFTY);
   voice.say (sp3_FOUR);
}
if (m==55){
   voice.say (sp3_FIFTY);
   voice.say (sp3_FIVE);
}
if (m==56){
   voice.say (sp3_FIFTY);
   voice.say (sp3_SIX);
}
if (m==57){
   voice.say (sp3_FIFTY);
   voice.say (sp3_SEVEN);
}
if (m==58){
   voice.say (sp3_FIFTY);
   voice.say (sp3_EIGHT);
}
if (m==59){
   voice.say (sp3_FIFTY);
   voice.say (sp3_NINE);
}
if (v==0){ 
  voice.say (sp3_A_M);  
}
if (v==1){
  voice.say(sp3_P_M);   
}
   delay (60000);
}

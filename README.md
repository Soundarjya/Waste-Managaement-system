# Waste-Managaement-system

CALL DELAY(delay, 100); DELAY Sor 100 microseconds

DETACH serve pin

for thisLed-0 to ledCount-1

SET ledPins (thisled) as OUTPUT:

for i in 0 to 2

BEGIN

cali height)call measure fil

CALL DELAY(delay, 1000); DELAY for 1000 microseconds

bin height (cali hight[0]-cali height[1]+cali height[2]/3; dat begin()

END

RETURN END

FUNCTION loop()

BEGIN for i in 0 to 2

BEGIN

aver amhili-measure_ambient_temperatun

CALL DELAY(delay, 10); DELAY for 10 microseconds dist ambi(aver ambi[0] aver_and[1] aver ambi[2])/

open/dist ambil

int fill level measure fill

int lodLevel mapefill level, 0, bin height, 0, ledCount

for this Led-0 to ledCount

BEGIN

if (thisled ledLevel) then

WRITE HIGH to ledPins(this.ed); else

WRITE HIGHo ledPins/thiet.edا

endif

valuet analogRead(xpin). value? analogRead(ypin)

Valueysample-

Valmal or Value>maxyVal or Value maxVal ValacVal or Valur maa Vathe

please) than

topple true

mdif

mickTime them PRINT "has

اشه

hamdhamidiry

hihimpute Holding, hum, If tham and to reshmi

الله

iftenan higher thrustad) then

END END RETURN END
 WRITEisevo pin,0), WRITE 0 to serve pin

CALL DELAY(delay, 100); DELAY Sor 100 microseconds

DETACH serve pin

for thisLed-0 to ledCount-1

SET ledPins (thisled) as OUTPUT:

for i in 0 to 2

BEGIN

cali height)call measure fil

CALL DELAY(delay, 1000); DELAY for 1000 microseconds

bin height (cali hight[0]-cali height[1]+cali height[2]/3; dat begin()

END

RETURN END

FUNCTION loop()

BEGIN for i in 0 to 2

BEGIN

aver amhili-measure_ambient_temperatun

CALL DELAY(delay, 10); DELAY for 10 microseconds dist ambi(aver ambi[0] aver_and[1] aver ambi[2])/

open/dist ambil

int fill level measure fill

int lodLevel mapefill level, 0, bin height, 0, ledCount

for this Led-0 to ledCount

BEGIN

if (thisled ledLevel) then

WRITE HIGH to ledPins(this.ed); else

WRITE HIGHo ledPins/thiet.edا

endif

valuet analogRead(xpin). value? analogRead(ypin)

Valueysample-

Valmal or Value>maxyVal or Value maxVal ValacVal or Valur maa Vathe

please) than

topple true

mdif

mickTime them PRINT "has

اشه

hamdhamidiry

hihimpute Holding, hum, If tham and to reshmi

الله

iftenan higher thrustad) then

END END RETURN END
 with the ESP8266

FUNCTION setup()

BEGIN

digitalWrite(BUILTIN_LED, HIGH);

dht.begin();

Print CONNECTING_TO;

PRINT (wifi-SSID()+","+wifi+psk());

wifi->connect();

while (WiFi.status() != WL CONNECTED) BEGIN // when wi-fi is connected

delay(500);

PRINT Ip++;

if (lp20)//When more than 20 lines are printed

break;

END

CLEAR BUFFER:

PRINT CONNECTED TO;

PRINT IP ADDRESS:

Start Firebase;

RETURN

END

FUNCTION Loop()

BEGIN

unsigned long currentMillis millis();

if (currentMillis-previousMillis > Interval or readTopple() is TRUE) then

BEGIN

previous Millis - currentMillis;

readHumidity(); // Reading humidity

read Temperature(); // Reading Temperature

readFillLevel(); //Reading Fill level

if (lp Ip time) then

BEGIN

Ip-0;

JsonObject &root=jsonBuffer.createObject();

Update JsonObject &root;

Firebase.push("/sensor/dht", root);

END

END

RETURN

END

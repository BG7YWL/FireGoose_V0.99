# FireGoose_V0.99
根据[FireGoose_V1.0][1]的资料画的PCB板

制作工艺

 - PCB制板:无铅 黑油喷锡
 - 过孔：盖油
 - 字印：白色
 - 尺寸： 长:17mm 宽：26mm 厚1.6mm 二层板

默认使用的是LED闪烁程序和HalfKay的引导程序，没有其他任何功能，也没有固化底层

```c
循环闪烁
// Simple LED blink

const int led = LED_BUILTIN;

void setup() {
  pinMode(led, OUTPUT);
}

void loop() {
  digitalWrite(led, HIGH);
  delay(100);
  digitalWrite(led, LOW);
  delay(100);
}
```


  [1]: https://github.com/RadioWar/FireGoose

# Robotbit MakeCode 擴充（課堂精簡版）

本儲存庫修改自 KittenBot 官方擴充 [pxt-robotbit](https://github.com/KittenBot/pxt-robotbit)（MIT 授權，版權歸原作者所有），供屏科大幼保系「程式教育機器人」課程使用。

- 保留：馬達（單顆速度、兩顆一起設、停止、停止所有馬達）、9g 舵機。
- 新增：RGB 燈積木（全部亮、第幾顆亮、亮幾顆、全部關燈、亮度），直接用 micro:bit 內建的 WS2812 函式控制板上 4 顆燈（P16），不再需要 neopixel 擴充。
- 隱藏（程式未刪，只是不顯示）：Geekservo、步進馬達、步進小車、延時馬達、LED 矩陣、超音波。
- 移除相依：neopixel、ModulePlus（SensorPlus）、microphone，工具箱只剩一個 Robotbit 分類。
- 注意：舊專案若用過原版的「RGB」積木搭配 Neopixel 積木，改用本擴充後要改用新的 RGB 積木。

---

# robotbit

Extension for Kittenbot Robotbit

## Feature

- Designed for robotic projects over microbit
- On board battery source
- Drive 8x servos and 4x DC motors and the same time (with 3.7v battery source to VM)
- Drive 2x Micro Stepper Motors
- On board buzzer
- On board 4x RGB Neo Pixels

# Blocks Preview
![image](https://user-images.githubusercontent.com/3390845/34512193-b3e0ffdc-f09b-11e7-839f-0c9c3563ac94.png)

# Hardware Preview
## Front
![image](https://user-images.githubusercontent.com/3390845/34511999-4b3fdef4-f09a-11e7-960e-5661268b0ba7.png)

## Back
![image](https://user-images.githubusercontent.com/3390845/34512098-04fecc1a-f09b-11e7-9ec6-62fcc0780773.png)


----------

For more infomation please visit [http://kittenbot.cc/bbs/](http://kittenbot.cc/bbs/ "Kittenbot BBS")

## License

MIT

## Supported targets

* for PXT/microbit
(The metadata above is needed for package search.)

```package
robotbit=github:Kittenbot/pxt-robotbit
```
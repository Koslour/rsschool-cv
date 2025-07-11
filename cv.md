# Stanislav Kazakov
![mountains](https://sun9-8.userapi.com/s/v1/ig2/mI6oTbBdy2pUiI7S99niZjZRvAjxywdSBQldaW3fuRZl9_wyXoYYywo65UnOPV0HnzdYsfPnqWbHrHA8galn8F6k.jpg?quality=95&as=32x47,48x70,72x105,108x157,160x233,240x349,360x523,480x698,540x785,640x930,720x1047,1080x1570,1280x1861,1440x2093,1761x2560&from=bu&cs=160x0 "Пейзаж с горами")
## My Contact Info:
* Phone: +8 953 965 43 59
* E-mail: acer.aspire.2017@yandex.ru
* GitHub: [Koslour](https://github.com/Koslour)
* Telegram: [Stanislav Kazakov](https://web.telegram.org/a/#1166847605)
## About Me
I am 26 years old, I work as an engineer. I want to try my hand at frontend development. I am sure that I will gain a lot of experience in this course. I like Web development.

* My strengths:
Quick learner
Full immersion in the essence of the problems
Diligence
Team playing
Keep learning…

## Skills
* C
* C++ (Qt)
* HTML
* CSS
* JavaScript
* Git/GitHub
## Code Examples
```
int readADC(char channel) {
    int Ain, AinLow;
    
    ADMUX = ADMUX | (channel & 0x0f);
    ADCSRA |= (1 << ADSC);
    while((ADCSRA & (1 << ADIF)) == 0);
    
    _delay_us(10);
    Ain = (int) ADC;

    return(Ain);  
}
```
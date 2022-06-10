![my-photo](./photo_1.jpg)
# Mikhail Sprygin
---
- discord wave#2204
- https://t.me/wave_103

# About me
My goal is to master a new profession. My passion is to realize own ideas into working projects. I have some knowledge and practice in design so I need skills to implement it at code.

I resort asking help in a pinch, prefer to find information by myself commonly. In working at a team I appreciate calmness, proffesional approach, mutual understanding and respect. 

# Code experience
I'm learning C for foundamential computer science understanding and HTML, CSS, JavaSctipt, Git at RS School.

This is example of my solution to reverse an order of given array at Codewars.
```
void digitize(uintmax_t n, uint8_t digits[], size_t *length_out)
{
    if (n == 0)
    {
        *length_out = 1;
        digits[0] = 0;
    }
    else
    {
        uintmax_t tmp = n;
        int i = 0;
        while (tmp >= 1)
        {
            tmp /= 10;
            i++;
        }
        *length_out = i;

        for (uintmax_t j = 0; j < i; j++)
        {
            digits[j] = n % 10;
            n = (n - n % 10) / 10;
        }
    }
}
```
# My working path
I was working as a web-designer and Internet marketing specialist at a factory. My main job was to collaborate with web-agency's programmers and give them designs and technical tasks. During my work I experienced programming occupation and decided to change my job.

# Education
Bachelor of Mechanical Engineering, Ivanovo State Power University.
Business English Course at Ivanovo State University.
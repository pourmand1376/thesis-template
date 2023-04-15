# Thesis Template

A LaTeX template for typesetting theses in Persian.

By: Hamid Zarrabi-Zadeh


I also added a script which generates dictionary automatically. For this, You use `\پاورق{#farsiArgument}{#EnglishArgument}` in any `.tex` file, then you can use `python generate_dictionary.py` to generate the dictionary automatically. 

Example (I use three lines, otherwise Github can not display it well):
```
\پاورق
{شبکه پیچشی عصبی}
{CNN}
```

Although I have added a python script to generate glossaries, I have understood that there is already a package to automatically do this. I do not have enough time to implement this. I leave these links for future generations! 
- [لاتک/وارد کردن واژه نامه و فهرست اختصارات با بسته glossaries - ویکی‌کتاب](https://fa.wikibooks.org/wiki/%D9%84%D8%A7%D8%AA%DA%A9/%D9%88%D8%A7%D8%B1%D8%AF_%DA%A9%D8%B1%D8%AF%D9%86_%D9%88%D8%A7%DA%98%D9%87_%D9%86%D8%A7%D9%85%D9%87_%D9%88_%D9%81%D9%87%D8%B1%D8%B3%D8%AA_%D8%A7%D8%AE%D8%AA%D8%B5%D8%A7%D8%B1%D8%A7%D8%AA_%D8%A8%D8%A7_%D8%A8%D8%B3%D8%AA%D9%87_glossaries)
- [ایجاد واژه نامه فارسی به انگلیسی در زی پرشین - پرسش و پاسخ پارسی‌لاتک](http://qa.parsilatex.com/6890/%D8%A7%DB%8C%D8%AC%D8%A7%D8%AF-%D9%88%D8%A7%DA%98%D9%87-%D9%86%D8%A7%D9%85%D9%87-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C-%D8%A8%D9%87-%D8%A7%D9%86%DA%AF%D9%84%DB%8C%D8%B3%DB%8C-%D8%AF%D8%B1-%D8%B2%DB%8C-%D9%BE%D8%B1%D8%B4%DB%8C%D9%86)
- [راهنمای ایجاد واژه‌نامه در زی‌پرشین « پارسی‌لاتک](http://parsilatex.com/site/1401/08/create-a-glossary-in-xepersian/)

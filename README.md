# baidu_trans: Free baidu translate API for Python

python 3.4+ 
python 2.7+

----------
Quickstart
----------
You can install it from PyPI:

code: bash

   $ pip install baidu_trans

or manual install:  
code: bash

   $ python setup.py install


~~~~~~~~~~~~~~~~~~~~~~~~~~~
single sentence translation
~~~~~~~~~~~~~~~~~~~~~~~~~~~

code: python

    >>> from baidu_trans import baidu_api
    >>> translator = baidu_api.Translator()
    >>> translator.translate('en', 'zh', 'hello world')
    u'你好，世界'


----------------
support language
----------------

.. code::  

  'afrikaans': 'af',  
  'arabic': 'ar',  
  'belarusian': 'be',  
  'bulgarian': 'bg',  
  'catalan': 'ca',  
  'czech': 'cs',  
  'welsh': 'cy',  
  'danish': 'da',  
  'german': 'de',  
  'greek': 'el',  
  'english': 'en',  
  'esperanto': 'eo',  
  'spanish': 'es',  
  'estonian': 'et',  
  'persian': 'fa',  
  'finnish': 'fi',  
  'french': 'fr',  
  'irish': 'ga',  
  'galician': 'gl',  
  'hindi': 'hi',  
  'croatian': 'hr',  
  'hungarian': 'hu',  
  'indonesian': 'id',  
  'icelandic': 'is',  
  'italian': 'it',  
  'hebrew': 'iw',  
  'japanese': 'ja',  
  'korean': 'ko',  
  'latin': 'la',  
  'lithuanian': 'lt',  
  'latvian': 'lv',  
  'macedonian': 'mk',  
  'malay': 'ms',  
  'maltese': 'mt',  
  'chinese_simplified': 'zh-CN',  
  'chinese_traditional': 'zh-TW',  
  'auto': 'auto'  
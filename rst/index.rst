---
title: ReStructuredText Cheatsheet
---

.. This is a comment! It will show up in the rendered markup.

Basics
------

- *emphasis*
- **boldface**
- ``code samples``
- Subscript: H\ :sub:`2`\ O
- Superscript: E = mc\ :sup:`2`
- This is `a reStructuredText primer`_.

.. _`a reStructuredText primer`: http://sphinx-doc.org/rest.html

Substitution
------------

I am |me|.

.. |me| replace:: 飞鸿

Definition list
---------------

学海无涯
  sea of learning, no horizon (idiom)
  
  no limits to what one still has to learn
  
  ars longa, vita brevis

Quoted paragraph
----------------

  云梦城之谜》带你穿梭明朝弄臣历史：开场悬疑，云梦泽凶案后，十年来朝中多次派人进入云梦泽搜索古城，每次都无功而返，古城就像消失了……清楚整件事来龙去脉者，只有五个半，五个人分别是皇上、权倾朝中的凤公公、厂卫第一高手季聂提、「御前猎手」辜月明，湖广布政史司钱世臣。另外半个，则是人称「道家行者」的戈墨，此人道法高明，有捉鬼驱魔的特殊本领。与辜月明更是势不两立。辜明月奉命要拿回楚盒与夫勐人头，他究竟能否解开云梦城消失之谜？解开自己害怕战争这无可告人的心结？千年前到底发生了什么事？为什么他们都曾像置身其中？而在千年后彼此纠缠不休。寻找真相的前路步步凶险，他能揭开整件事是鬼神之力亦或是政治之谜？
  
Line blocks
-----------

| Your bulge draws my eye
| And now it is too awkward
| To look at your face

Footnotes
---------

An HTTP GET request [#]_ is made to the URL.

The result you get back is not plain text—rather, it is JSON [#]_.

Directives
----------

.. tip:: Floss every day.
   It is not enough to just brush!

   - The note contains all indented body elements
     following.
   - It includes this bullet list.
   
.. image:: http://i.giphy.com/xj3Ie4rLNuLSM.gif

Code blocks
-----------

.. code:: python

  def my_function():
      "just a test"
      print 8/2

.. [#] HTTP GET is a type of web request that is used for retrieving data from a server.
.. [#] JSON stands for JavaScript Object Notation.

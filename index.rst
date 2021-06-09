Ezsend Documentation
====================

Installation
^^^^^^^^^^^^

Ezsend can be installed using pip To install open your terminal/command
prompt and enter:

.. code:: terminal

    $ pip install ezsend

Importing ezsend
^^^^^^^^^^^^^^^^

Before you can use ezsend you must import ezsend To do that open your
python shell and enter the following command:

.. code:: python

    import ezsend

Adding your email account
^^^^^^^^^^^^^^^^^^^^^^^^^

Before you can text or email with ezsend you must add your email account
To add your account enter the following command:

.. code:: python

    ezsend.add(youremail, youremailaccountpassword, thenameyouwouldliketonameyouraccount)

Sending an email
^^^^^^^^^^^^^^^^

To send an email enter the following command:

.. code:: python

    ezsend.send(thenameyounamedyouraccount, thereceiversemail, thesubjectofyourmessage, thebodyofyourmessage)

Sending a text
^^^^^^^^^^^^^^

To send a text enter the following command:

.. code:: python

	ezsend.text(thenameyounamedyouraccount, thereceiversemail, the receiverscarrier, thesubjectofyourmessage, thebodyofyourmessage)

Example - Adding
^^^^^^^^^^^^^^^^

Lets say I wanted to add a account named "gmail"

.. code:: python

    import ezsend
    ezsend.add('gmail', 'myemail@provider.com', 'myemailaccountpassword')

Example - Email
^^^^^^^^^^^^^^^

Lets say I wanted to send an email to "example@provider.com" with a
subject of "Hi" and a body of "Hello"

.. code:: python

    import ezsend
    ezsend.send('gmail', 'example@provider.com', 'Hi', 'Hello')

Example - Text
^^^^^^^^^^^^^^

Lets say I wanted to send a text to "2345678901" with a subject of "Hi"
and a body of "Hello"

.. code:: python

    import ezsend
    ezsend.text('gmail', '2345678901', 'verizon', 'Hi', 'Hello')


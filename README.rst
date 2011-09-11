============
NumberPicker
============

This is a numberpicker widget for android.
In ascii it looks something like this::

   ++++
   0012
   ----

Requirements
------------

Following requirements are needed:

* android 1.6 (API4) >=

Installation
------------

Copy the ``drawables`` and also the ``com.oldsch00l.NumberPicker.java``
folder into your project. Except the ``com.oldsch00l.NumberPickerActivity.java``,
which is only the sample activity.

Usage
-----

You can simply use the numberpicker widget in you layout xml file::

    <com.oldsch00l.NumberPicker xmlns:np="http://oldsch00l.com/android/numberpicker"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        np:digits="4"
    />

Parameters
----------

digits
  Number of digits to show.



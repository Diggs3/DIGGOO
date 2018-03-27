Commands
========


For
---

* ``for(int Variable Name, int Start Value, int End Value, int diffrens Value);``

* **int Variable Name:**

  - ``a int vareable that its going to br created.``

* **int Start Value:**

  - ``start value.``

* **int End Value:**

  - ``end value.``

* **int diffrens Value:**

  - ``the diffrens betwin every time the loop runs.``

* **example 1:**

  - ``the folowing example will create 10 integers with (i)'s value as its name. (int) == id of variable you seking" in "code" you get the values by using int&(int). in C# you get it by using values[ (int) ].``

  - **code**::

		for(i, 0, 10, 1);
			int(int&i, int&i);
		end();

  - **code C# relevant**::

		list<int> values = new list<int>();
		for(int i = 0, i > 10, i++)
		{
			values.add(i);
		}

* **example 2:**

  - the folowing example will is like the last but insted of having posetive end value we have a negative.

  - **code**::

    for(i, 0, -10, -1);
      int(int&i, int&i);
    end();

  - **code C# relevant**::

		list<int> values = new list<int>();
		for(int i = 0, i < -10, i--)
		{
			values.add(i+10); //you cant have negative values like "code".
		}
	
* **example 3:**

  - the folowing example will 

  - **code**::
	
		new(x, file&wal.png);

		new(y);
		for(i, 0, 10, 1);
			ImgFilter(x, file&filter.png, y);
				
		save(y, file&image@int&i@.png);	
			end();
		code C# relevant:
			Bitmap image = (Bitmap) Image.FromFile(@"C:\Documents and Settings\" + @"All Users\Documents\My Documents\image.png", true);
			for(int i = 0, i > 10, i++)
			{
				exportedImage = aFunktionReleventToFilter(image);
				exportedImage.Save("image" + i + ".png");
				image = exportedImage;
			}


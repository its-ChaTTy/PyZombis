-------------------
PyScript Component
-------------------


.. activecode:: pyscript_component_12
   :nocodelens:
   :language: python3
   :python3_interpreter: pyscript

   import pandas as pd

   # Create a simple DataFrame
   data = {'Name': ['John', 'Anna', 'Peter', 'Linda'],
         'Age': [28, 34, 29, 32],
         'City': ['New York', 'Paris', 'Berlin', 'London']}

   df = pd.DataFrame(data)

   # Display the DataFrame
   print(df)


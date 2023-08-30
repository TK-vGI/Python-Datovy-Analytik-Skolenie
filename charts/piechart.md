# Piechart

A pie chart is a circular chart which is divided into slices to illustrate numerical proportion.

```python
#!/usr/bin/python

import matplotlib.pyplot as plt
 
labels = ['Oranges', 'Pears', 'Plums', 'Blueberries']
quantity = [38, 45, 24, 10]

colors = ['yellowgreen', 'gold', 'lightskyblue', 'lightcoral']

plt.pie(quantity, labels=labels, colors=colors, autopct='%1.1f%%', 
    shadow=True, startangle=90)

plt.axis('equal')

plt.savefig('piechart.png')
```

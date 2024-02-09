### Αλλαγή εικονιδίων της Χελώνας Python

Αντί να χρησιμοποιείτε πάντα μια Χελώνα, μπορείτε να πείτε στο εικονίδιο της Χελώνας Python να χρησιμοποιήσει μια διαφορετική εικόνα. Η εικόνα πρέπει να είναι μικρή, ώστε να μην καλύπτει πάρα πολύ μεγάλο τμήμα της οθόνης: 50 × 50 pixels θα σας δώσουν ένα μεγάλο εικονίδιο.

+ Πρώτα πρέπει να καταχωρίσετε την εικόνα με την `screen`:

```python
screen = turtle.Screen ()
screen.register_shape ('happy.png') 
```

+ Στη συνέχεια μπορείτε να ορίσετε την `shape`:

```python
turtle.shape ('happy.png')
```

+ Ο αρχικός προσανατολισμός των εικονιδίων Χελώνας είναι προς τα δεξιά. Μπορείτε να αλλάξετε την κατεύθυνση για να κάνετε την εικόνα σας να κοιτάει προς τα πάνω:

```python
turtle.setheading(90) # face upwards
```

Δείτε ένα παράδειγμα εδώ: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
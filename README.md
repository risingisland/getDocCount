# getDocCount
Display the number of documents in a folder for EvolutionCMS.

---------

Sampling by DocLister parameters.

### SNIPPET PARAMETERS
* **&parents** - The ID of the folder you wish to count the containts of.
* **&round** - Number of decimals to round up to (ex.: your count is 4 and round is set to 1, your result would be 10).

### Example Calls:
```[[getDocCount? &parents=`2` &round=`2`]]```

```[[getDocCount? &parents=`2,15` &round=`0`]]```

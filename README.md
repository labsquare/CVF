# CVF-
Cute Variant Format

```
{
  
"meta":{
  "caller": "truc"
  
},

"variants": [
  
  {
    "chr": "chr1",
    "pos": 22424,
    "transcript": "NM_32424",
    "cdna": "c.23424",
    "gene": "CFTR",
    "ann1": "value",
    "ann2": "value",
    "ann3": "value",
    "gnomAF": 23,
    "gnomEU": 24,
    "SIFT": 24,

    "ann4": {
      "value": 234,
      "tooltip": "CECI terst"
    }
    ,
    
    "ranking": "score",
    "samples": [
      {
        "name":"boby",
        "genotype":{
          "GT":"0/1",
          "AF": 24
        }
      }
      ]
    
  },
    {
    "chr": "chr1",
    "pos": 22424,
    "transcript": "NM_222222",
    "ann1": "value",
    "ann2": "value",
    "ann3": "value",
    "ann4": "value"
    
  },
    {
    "chr": "chr1",
    "pos": 22424,
    "ann1": "value",
    "ann2": "value",
    "ann3": "value",
    "ann4": "value"
    
  }
  
  ],
  
  "set": [
    
    {
    "name": "denovo",
    "variants": [1,4,5,65]
      
    },
       {
    "name": "hetero",
    "variants": [1,4,5,65]
      
    }
    
    
    ],
    
  "visible": [
    
    {
      "sortedFields": ["ranking","gene","ann1","ann2","chr","pos"]
      
    }    
      
      
    ]
}

```

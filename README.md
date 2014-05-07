hive-examples
=============

##HiveQL examples:  my notes on using hive

There are three ways to run hive:

Interactively

    hive

From a file

    hive -f <file name>
    
In-line

    hive -e 'select * from mytable'

To view the available functions in Hive

    show functions;
    
Then to view the function

    describe function corr;
    corr(X,Y) - Returns the Pearson coefficient of correlation between a set of number pairs

To see the tables

    show tables;
    
        hive>show tables;
        sample_07
        sample_08
        Time taken: 0.772 seconds, Fetched 2 row(s)
    
To see the schema:  column names and data types

    describe <table name>;
    
Linux CLI - pull down sample data

    wget --output-document=ml-10m.zip   http://files.grouplens.org/papers/ml-10m.zip

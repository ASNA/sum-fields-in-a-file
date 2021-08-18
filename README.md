SumFields is a command line-driven program that sums up to twelve fields in a given file for auditing purposes. 

![](https://asna.com/filebin/marketing/cmd_pNdlG7xaxE.png)

It needs four required command line arguments: 

`--databasename or -d`: The database name
`--library or -l`: The library name
`--file or -f`: The file name
`--fields or -fs`: A comma-separated list of up to 12 field names (in double quotes)

For example, this command line:


    sumfields -d "*Public/DG Net Local" -l examples -f cmsales -fields "jan, feb, mar"

    
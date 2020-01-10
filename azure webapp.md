## Azure WebApp

1.  Login into portal.azure.com
2.  Click `Create resource` > `Web` > `WebApp`
3.  Enter following details:
    ```yml
    ResourceGroup: mygroup1 [Use Create New link]
    Name:   maxunlimited    [Use some other Unique name]
    Publish: Code 
    Runtime-Stack: ASP.NET v4.7
    Sku-Size: Free F1       [Under Dev/Test Tab]
    ```

4.  Click `Next` button and then choose 'NO' for Application Insights

5.  Click `Create` button and wait for appliation to be ready
6.  Use `Browse` button to view the final website

# Make the following tables

<img src="https://user-images.githubusercontent.com/56488686/162629056-3a1d0e13-d091-4dfe-88a8-95541d0ba009.gif" alt="table" width="300">

### Table simple
<img src="https://user-images.githubusercontent.com/56488686/162629082-00713046-6dd7-4732-a42f-090f4672fc3e.png" alt="table simple" width="600">

Make this tables with the following labels
```HTML
    <!-- Generate a table -->
    <table>
        <!-- Generate row -->
        <tr>
            <!-- Generate column head -->
            <th></th>
        </tr>
        
        <!-- Generate row -->
        <tr>
            <!-- Generate column -->
            <td></td>
        </tr>
    </table>
```


### Table complex
<img src="https://user-images.githubusercontent.com/56488686/162629111-9624f523-3e97-4231-ac1a-453bc94c7e6d.png" alt="table complex" width="800">

Make this tables with the following labels
Note: use `colspan` to merge columns
```HTML
    <!-- Generate a table -->
    <table>
        <!-- Specific label of head-->
        <thead>
            <tr>
                <th></th>
            </tr>
        </thead>

        <!-- Specific label of body-->
        <tbody>
            <tr>
                <td></td>
            </tr>
        </tbody>

        <!-- Specific label of footer-->
        <tfoot>
            <tr>
                <td></td>
            </tr>
        </tfoot>
    </table>
```

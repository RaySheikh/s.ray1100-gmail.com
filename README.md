## [Blazor BootStrap4 Tables](https://github.com/RaySheikh/Blazor-Bootstrap4-Table/)

Works with Blazor Serverside project.

[Install using nuget package manager:](https://www.nuget.org/packages/BlazorBootstrap4Table/)
```
Install-Package BlazorBootstra4Table -Version 1.0.1
```
Usage:
```
@using BlazorBootstrap4Table
  
<Table Items="@users">
    <TableHeader>
        <th>First Name</th>
        <th>Last Name</th>
        <th>Email</th>
    </TableHeader>
    <TableRow>
        <td>@context.FirstName</td>
        <td>@context.LastName</td>
        <td>@context.Email</td>
    </TableRow>
</Table>

@code {
  //Takes list
  List<User> users {get; set;}

}
```
Please reference latest boostrap 4 stylesheet in _Host.cshtml head tag.

### Future Enhancements:

- Pagination
- Sorting
- Search
- Responsive


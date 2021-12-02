## Intoduction 

Sometime we need to all bangladeshi divisions and district data in sql format but it's hard to find it in open source. That's why I made 
bangladeshi all division and bangladeshi all district data in sql format.

### SQL Table(s)

What things you need to install the software and how to install them
```SQL
USE [BDInfo]
GO
/****** Object:  Table [dbo].[District]    Script Date: 2/18/2020 5:18:35 PM ******/
SET ANSI_NULLS ON
GO
SET QUOTED_IDENTIFIER ON
GO
CREATE TABLE [dbo].[District](
	[Id] [int] NOT NULL,
	[Name] [varchar](100) NOT NULL,
	[DistrictId] [int] NOT NULL,
 CONSTRAINT [PK_District] PRIMARY KEY CLUSTERED 
(
	[Id] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON [PRIMARY]
) ON [PRIMARY]
GO
/****** Object:  Table [dbo].[Division]    Script Date: 2/18/2020 5:18:35 PM ******/
SET ANSI_NULLS ON
GO
SET QUOTED_IDENTIFIER ON
GO
CREATE TABLE [dbo].[Division](
	[Id] [int] NOT NULL,
	[Name] [varchar](100) NOT NULL,
 CONSTRAINT [PK_Division] PRIMARY KEY CLUSTERED 
(
	[Id] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON [PRIMARY]
) ON [PRIMARY]
GO
```
### SQL Table Sample Data For Bangladeshi Division(s)
```SQL
INSERT [dbo].[Division] ([Id], [Name]) VALUES (1, N'Chattogram')
INSERT [dbo].[Division] ([Id], [Name]) VALUES (2, N'Rajshahi')
```

### SQL Table Sample Data For Bangladeshi District(s)

```SQL
INSERT [dbo].[District] ([Id], [Name], [DivisionId]) VALUES (1, N'Cumilla', 1)
INSERT [dbo].[District] ([Id], [Name], [DivisionId]) VALUES (2, N'Feni', 1)
INSERT [dbo].[District] ([Id], [Name], [DivisionId]) VALUES (13, N'Pabna', 2)
INSERT [dbo].[District] ([Id], [Name], [DivisionId]) VALUES (14, N'Bogura', 2)
```

## Built With

* [SQL Server 2017](https://www.microsoft.com/en-us/sql-server/sql-server-2017) - The web framework used
 
## Author

* **Raju Ahmed** - *Initial work* - [RajuAhmed](https://github.com/mrajuahmed)

## Note : 
* It can be changed on administrative changes by the Bangladeshi Govt.


<h1 align="center">The End</h1>

<table align="center">
<tr><th>Find me on following(s)</th><th>Support me on</th></tr>
<tr><td>

| [<img src="https://github.com/irajuahmed/irajuahmed/blob/main/images/github.png" alt="github logo" width="34">](https://github.com/irajuahmed) | [<img src="https://github.com/irajuahmed/irajuahmed/blob/main/images/instagram.jpg" alt="instagram logo" width="24">](https://www.instagram.com/marginalraju/) | [<img src="https://github.com/irajuahmed/irajuahmed/blob/main/images/Linkedin.png" alt="Linkedin Logo" width="24">](https://www.linkedin.com/in/raju-ahmed-263475126/)| [<img src="https://github.com/irajuahmed/irajuahmed/blob/main/images/stack.svg" alt="stack logo" width="24">](https://stackoverflow.com/users/5615778) 
|---|---|---|---|

</td><td>

<p><a href="https://www.buymeacoffee.com/https://www.buymeacoffee.com/mIUyB3X5P"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="https://www.buymeacoffee.com/mIUyB3X5P" /></a></p>

</td></tr> </table>

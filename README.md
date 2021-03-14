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


<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/www.linkedin.com/in/raju-ahmed-263475126" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="www.linkedin.com/in/raju-ahmed-263475126" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/5615778" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/stackoverflow.svg" alt="5615778" height="30" width="40" /></a>
</p>


<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/https://www.buymeacoffee.com/mIUyB3X5P"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="https://www.buymeacoffee.com/mIUyB3X5P" /></a></p><br><br>


# Rentify — ASP.NET 8 Razor Pages

Razor Pages app (.NET 8) with a 4-layer architecture: **BusinessObjects → Repositories → Services → Web**. Uses EF Core, DI, and SignalR.

![dotnet](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet&logoColor=white)
![license](https://img.shields.io/badge/license-MIT-blue)

---

## Solution Structure
```text
PRN222_GR3_Rentify/
├─ 1. RazorWebApp/
│  └─ Rentify.RazorWebApp/
│     ├─ Pages/
│     │  ├─ Account/
│     │  ├─ Admin/
│     │  ├─ ChatPages/
│     │  ├─ InquiryPages/
│     │  ├─ ItemPages/
│     │  ├─ PostPages/
│     │  ├─ Role/
│     │  └─ Shared/
│     ├─ DependencyInjection/
│     ├─ wwwroot/
│     ├─ Program.cs
│     ├─ _ViewImports.cshtml
│     ├─ _ViewStart.cshtml
│     ├─ Error.cshtml
│     ├─ Index.cshtml
│     └─ Privacy.cshtml
├─ 2. Service/
│  └─ Rentify.Services/
│     ├─ ExternalService/
│     ├─ Hub/
│     ├─ Interface/
│     ├─ Mapper/
│     └─ Service/
├─ 3. Repository/
│  └─ Rentify.Repositories/
│     ├─ Infrastructure/
│     ├─ Implement/
│     ├─ Interface/
│     ├─ Helper/
│     └─ Repository/
└─ 4. BusinessObject/
   └─ Rentify.BusinessObjects/
      ├─ ApplicationDbContext/
      ├─ DTO/
      ├─ Entities/
      └─ Enum/
```
## Features
- User/Role and OTP.
- Category, Item, Post.
- Rental and RentalItem.
- Inquiry and Comment.
- Real-time chat via SignalR.
- Razor Pages for Admin/User/Item/Post/Inquiry/Chat areas.

## Requirements
- .NET SDK **8.0+**
- SQL Server for dev (can switch to PostgreSQL/SQLite).

## Quickstart
```bash
git clone https://github.com/thiennlse/rentify
cd https://github.com/thiennlse/rentify
```

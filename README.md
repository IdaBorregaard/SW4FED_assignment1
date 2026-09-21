BilvaerkstedApp/
├── Models/              # Datamodeller (Database tabeller)
│   ├── WorkOrder.cs     # Opgave/Ordre (Krav 1 & 2)
│   └── Invoice.cs       # Faktura (Krav 3 & 4)
│
├── Services/            # Logik og databasehåndtering
│   └── DatabaseService.cs
│
├── ViewModels/          # Logik til binding med UI
│   ├── BaseViewModel.cs
│   ├── CreateOrderViewModel.cs
│   ├── CalendarViewModel.cs
│   ├── CreateInvoiceViewModel.cs
│   └── InvoiceListViewModel.cs
│
├── Views/               # XAML-sider (UI)
│   ├── CreateOrderPage.xaml
│   ├── CalendarPage.xaml
│   ├── CreateInvoicePage.xaml
│   └── InvoicePage.xaml
│
└── Resources/
    └── Styles/          # Styling og farver
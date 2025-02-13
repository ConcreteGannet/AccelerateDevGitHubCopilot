# Library App

## Description
Library App is a console application for managing a library system. It allows users to search for patrons, renew memberships, return loaned books, and extend book loans.
## Table of Contents
- [Description](#description)
- [Key Classes and Interfaces](#key-classes-and-interfaces)
- [Usage](#usage)
- [License](#license)
## Key Classes and Interfaces
- **Entities**
  - [`Author`](src/Library.ApplicationCore/Entities/Author.cs)
  - [`Book`](src/Library.ApplicationCore/Entities/Book.cs)
  - [`BookItem`](src/Library.ApplicationCore/Entities/BookItem.cs)
  - [`Loan`](src/Library.ApplicationCore/Entities/Loan.cs)
  - [`Patron`](src/Library.ApplicationCore/Entities/Patron.cs)

- **Enums**
  - [`EnumHelper`](src/Library.ApplicationCore/Enums/EnumHelper.cs)
  - [`LoanExtensionStatus`](src/Library.ApplicationCore/Enums/LoanExtensionStatus.cs)
  - [`LoanReturnStatus`](src/Library.ApplicationCore/Enums/LoanReturnStatus.cs)
  - [`MembershipRenewalStatus`](src/Library.ApplicationCore/Enums/MembershipRenewalStatus.cs)

- **Interfaces**
  - [`ILoanRepository`](src/Library.ApplicationCore/Interfaces/ILoanRepository.cs)
  - [`ILoanService`](src/Library.ApplicationCore/Interfaces/ILoanService.cs)
  - [`IPatronRepository`](src/Library.ApplicationCore/Interfaces/IPatronRepository.cs)
  - [`IPatronService`](src/Library.ApplicationCore/Interfaces/IPatronService.cs)

- **Services**
  - [`LoanService`](src/Library.ApplicationCore/Services/LoanService.cs)
  - [`PatronService`](src/Library.ApplicationCore/Services/PatronService.cs)

- **Console**
  - [`ConsoleApp`](src/Library.Console/ConsoleApp.cs)
  - [`Program`](src/Library.Console/Program.cs)

- **Infrastructure**
  - [`JsonData`](src/Library.Infrastructure/Data/JsonData.cs)
  - [`JsonLoanRepository`](src/Library.Infrastructure/Data/JsonLoanRepository.cs)
  - [`JsonPatronRepository`](src/Library.Infrastructure/Data/JsonPatronRepository.cs)

## Usage
To run the application, execute the following command in the root directory:

```sh
dotnet run --project src/Library.Console/Library.Console.csproj
```

# License
This project is licensed under the MIT License.

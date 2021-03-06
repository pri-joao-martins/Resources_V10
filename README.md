# Resources V10
In this repository you will find several resources and code samples to accelerate your integration with PRIMAVERABSS ERP V10.

### What is PRIMAVERA V10?
First of all, PRIMAVERA is a company specialized in the development of management solutions (*ERP - Enterprise Resource Planning*) for small, medium and large companies. PRIMAVERA's ERP 10 has a set of extensibility technologies that enable third-party applications to extend the base functionality or add new in order to provide richer solutions to the end customer.

The PRIMAVERA V10 is a solution that runs on Windows plataform, witch is developed on the .NET framework (*C#*) and SQL Server.

### How to use the API?
To start developing a third-party application with Visual Studio you need:
1. A local installation of PRIMAVERA ERP 10.
2. Reference to .NET Framework 4.7.
3. Add to your project a reference to `ERPBS100.DLL`. This will provide access to all available modules.
4. Add to your project a reference to the module that you want work with, for sales add `VndBE100.DLL`.
5. Add to your project a reference to `StdBE100.DLL`. This will provide access to enumeration types and some base entities.
6. Set the output path for your solution.
7. Finally you can start coding your project.

### Contributing and Feedback
Everyone is free to contribute to the repository.

Any bugs detected in the code samples can be reported in the *Issues* section of this repository.

### License
Unless otherwise specified, the code samples are released under the MIT license.

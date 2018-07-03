
# Server Setup

### Initializing & Running The Server Locally

![](https://github.com/YoniProbeh/RentalAPI/blob/master/Server/Library/img/build-min.gif?raw=true)

**As Displayed Above, To Initalize The Server You Must First Open The Solution In Visual Studio**
1. Go To The Package Manager Console At The Bottom Of The Screen
2. Select "Data" As The Default Project
3. In The Solution Explorer, Right Click On The "Data" Project" => Select `Set As Startup Project`
4. Enter `Update-Database` => Click Enter (Verifying That All Seed Methods Were Executed And The Database Is Updated Accordingly
5. In The Solution Explorer, Right Click On The "Server" Project => Select `Setup As Default Project`
6. Now Press `ctrl+F5` To Compile And Run The Application
7. To Test The API's Quality, Navigate In The Browser To `https://localhost:56004/api/Vehicles` To See If Any Values Were Retrieved
=================================================================================

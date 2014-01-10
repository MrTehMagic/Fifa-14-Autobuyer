var loginDetails = new LoginDetails("e-mail", "password", "secret answer", Platform.Ps3 /* or Platform.Xbox360 / Platform.Pc */);
var loginResponse = await client.LoginAsync(loginDetails);

var searchParameters = new PlayerSearchParameters
{
    Page = 1,
    Level = Level.Gold,
    ChemistryStyle = ChemistryStyle.Sniper,
    League = League.BarclaysPremierLeague,

var tradePileResponse = await client.GetTradePileAsync();

var purchasedItemsResponse = await client.GetPurchasedItemsAsync();

var searchParameters = new DevelopmentSearchParameters
{
    Page = 1,
    Level = Level.Gold,
    DevelopmentType = DevelopmentType.Healing,
};

var searchResponse = await client.SearchAsync(searchParameters);
foreach (var auctionInfo in searchResponse.AuctionInfo)


    Nation = Nation.Norway,
    Position = Position.Striker,
    Team = Team.ManchesterUnited
};

var searchResponse = await client.SearchAsync(searchParameters);
foreach (var auctionInfo in searchResponse.AuctionInfo)
{
    // Handle auction data
}

var auctionResponse = await client.PlaceBidAsync(auctionInfo, 150);

var auctionResponse = await client.PlaceBidAsync(auctionInfo);

var auctionResponse = await client.GetTradeStatusAsync(
    Auctions // Contains the auctions we're currently watching
    .Where(x => x.AuctionInfo.Expires != -1) // Not expired
    .Select(x => x.AuctionInfo.TradeId));

foreach (var auctionInfo in auctionResponse.AuctionInfo)
{
    // Handle the updated auction data
}

var item = await client.GetItemAsync(auctionInfo);

var imageBytes = await client.GetPlayerImageAsync(auctionInfo);

var creditsResponse = await client.GetCreditsAsync();

var auctionDetails = new AuctionDetails(auctionInfo.ItemData.Id);

var auctionDetails = new AuctionDetails(auctionInfo.ItemData.Id, AuctionDuration.ThreeHours, 200, 1000);

var listAuctionResponse = await client.ListAuctionAsync(auctionDetails);

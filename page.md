# Performance

After we install service for new customers – they often tell us that Netflix, web browsing, and gaming “just feel faster” using YOUR_ISP. This is thanks to some smart software we helped develop based on decades of research.

Most Internet Service Providers focus solely on bandwidth (Megabits-per-second, or Mbps), because it is the simplest metric to advertise. But in addition to offering high bandwidth, YOUR_ISP also delivers connectivity with low latency, high responsiveness, and Whole-Home WiFi for thorough coverage. Achieving optimal performance in these multiple areas is the key to an internet connection that feels fast, stable, and responsive.

## Whole-Home Mesh WiFi

Most Internet Service Providers provide customers a single WiFi router, capable of covering around 1500 sqft. With just a single router, wireless connections often degrade past that range – causing WiFi performance issues in the far ends of the home.

We take a more proactive approach – providing our customers with a Mesh WiFi 6E system. This ensures thorough WiFi coverage across every room of the home.

## What is Speed? - Bandwidth vs Latency

Bandwidth is the maximum amount of data that can be transmitted over an internet connection, usually measured in Megabits-per-second.

Latency is delay, and can be thought of as the time it takes a message sent from your device to reach its destination, plus the time it takes to receive a response back. Latency is measured in milliseconds (ms).

Bandwidth affects how long it takes to download or upload large static files (game release downloads, video editing files). For other daily internet tasks (video streaming, VoIP,  conference calling, gaming) – performance comes down to Latency, and Latency under Load (bufferbloat).

Bandwidth does not impact internet performance as much as advertising would lead us to believe. Here is an excerpt from the recent research paper Understanding the Metrics of Internet Broadband Access: How Much Is Enough?

    Above about 20 mb/s, adding more speed does not improve the load time. The limit on the load time is the latency to the servers providing the elements of the web page.
    Understanding the Metrics of Internet Broadband Access: How Much Is Enough?

The world’s largest Content Distribution Network, Cloudflare, has confirmed observing this pattern in the data flowing across their worldwide network.

Source: Cloudflare: Making home Internet faster has little to do with “speed”:

Internet researchers with the Broadband Internet Technical Advisory Group have also come to this same conclusion in their research paper, Latency Explained.

    Web page load time is largely determined not by throughput, but by two other factors: how long a network round-trip takes, and how many network round-trips are required.
    Broadband Internet Technical Advisory Group - Latency Explained

The average household uses just 5 Mbps of bandwidth during peak usage hours, and only 2.5% of residential internet users use more than 32 Mbps during peak hours. While Internet Service Providers advertise plans in terms of bandwidth, they completely neglect latency – which determines our actual experience of the internet day-to-day.

    The less delay that a network or application has, the more “responsive” a service will feel to an end user. The more delay (or lag), the worse it will feel.

    Critically, however, reducing delay meaningfully improves all existing user applications.
    Broadband Internet Technical Advisory Group - Latency Explained

This effect is seen most clearly with online gaming, which uses less than 1 Mbps in each direction, but demands very stable, low latency. Recent consumer research confirms that latency is more important than bandwidth for online gaming.

    Overall, the consistently reinforced takeaway is that latency has now clearly overtaken broadband speed as the focus area for network providers seeking to provide – and guarantee and commercially benefit from – optimum experience in both online multiplayer and cloud gaming.
    GameBench - Network Performance and Gamer Experience

## Latency Under Load / Bufferbloat

Many of us take it for granted that it is “normal” for a video conference call to stutter or disconnect when someone else on the same home network is watching a 4K video. That is actually a symptom of Bufferbloat – the undesirable latency that results from network equipment buffering too much data. Connections with high Bufferbloat have lower perceived responsiveness. Cable and DSL internet services suffer from significant Bufferbloat, which can make these connections feel slow even when speed tests show normal bandwidth (Mbps).

YOUR_ISP has developed a Quality of Experience solution called LibreQoS. This software keeps our customers’ latency and bufferbloat as low as possible, providing a more streamlined internet experience. With LibreQoS, your WiFi calls, zoom calls, and online games are given fair priority, even when large file downloads or other so-called “bulk” tasks are occurring in the background. This allows YOUR_ISP to provide a more responsive and “snappy” experience using the internet, compared to alternatives like Cable Internet, 5G, or Fiber.

In recent years, internet researchers have come to find that reducing Bufferbloat is crucial for improving internet performance.

    Queue management techniques such as Active Queue Management are available that will reduce bufferbloat in network bottleneck equipment by triggering applications to reduce the amount of queuing delay that they cause. This is not theoretical; AQM has been proven to work at scale in DOCSIS and other networks.

    In addition, it is also important to have a consistently responsive service where delay stays consistently low no matter how heavily utilized a user’s Internet connection may be and no matter what mix of applications are being used. This might seem like an unreasonable demand — expecting a network to be able to provide consistently low delay even under heavy load — but, as this report shows, this is in fact possible with today’s technology.
    Broadband Internet Technical Advisory Group - Latency Explained

Find out if you experience Bufferbloat on your home internet connection using the Waveform Bufferbloat Test.
Waveform Bufferbloat Test

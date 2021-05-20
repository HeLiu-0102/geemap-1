in this video I'm going to show you how to use base maps from the internet and how to add those base maps to interactive map using the GEE map Python package .

在这段视频中，我将向您展示如何使用互联网上的基础地图，以及如何使用GEEmap Python包将这些基础地图添加到交互式地图中。

so in the previous video I already show you how to use Conda to install the package and how to use Dukla notebook to create interactive map .

所以在上一个视频中，我已经向您展示了如何使用Conda安装包，以及如何使用Dukla笔记本创建交互式地图。

so for today we're going to look into how to use base maps and first of all we need to open the terminal and - so what Condor environment .

所以今天我们将研究如何使用底图，首先我们需要打开终端，那么什么是秃鹰环境。

let me create it so you can type a command under MV list to show you he Conrad environment already on your computer .

让我来创建它，这样你就可以在MV list下键入一个命令来显示你的计算机上已经有了Conrad环境。

so for today we're going to use the G condyle environment .

所以今天我们要使用G髁状突环境。

so all we need to do is convert activate G and then once you are inside in Guam I can't exactly the notebook enter is to open a new tab on your browser .

所以我们需要做的就是转换激活G，然后一旦你在关岛，我不能确切的笔记本输入是打开一个新的标签在你的浏览器。

so then from here we can start create notebook we are going to use the folder that we created and then we are going to create a new one Jupiter notebook .

因此，我们可以从这里开始创建笔记本，我们将使用我们创建的文件夹，然后我们将创建一个新的笔记本。

so from here we can change the name of the notebook  for example Bates make .

所以从这里我们可以改变笔记本的名字，比如贝茨做的。

okay and so this is the introduction for the GE map passing package. 

好的，这是对GE-map-passing包的介绍。

if you don't know this mikandi map on your Google Gmail pickup then you should be able to find the github page at the first link just click .

如果你不知道谷歌Gmail皮卡上的mikandi地图，那么你应该可以在第一个链接找到github页面，只需单击。

so here so Zod the source code and you can directly scroll down to here to the you see space. 

所以这里让Zod的源代码，你可以直接滚动到这里，你看到的空间。

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mcZKT0.RptOyjYemAkBpzdPNx5qGJzisMpgaozi4AGi6BuM0Lca53PZNuRDr5GVDWfDpOnpdr4bxhPlDd5v5xBTo!/b&bo=gAc4BIAHOAQDORw!&rf=viewer_4)

in here I show you some examples that how you can create a map .

在这里，我将向您展示一些如何创建地图的示例。

```python
import geemap
Map = geemap.Map(center=[40,-100], zoom=4)
```

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mcZKT0.RptOyjYemAkBpzdPPPUbZZvSw2vurGr6l4hsR4NQ1OGgsfoGWquSacboV9Xdce42*e0KqdOYU89o3fTgc!/b&bo=fQc4BH0HOAQDaUw!&rf=viewer_4)

okay ,so for example ,you can't already just copy this one and then come back to the noble case .

好吧，举个例子，你不能复制这个，然后再回到高端的案子。

so all I need to do just out enter and you should see this interactive map right away. 

所以我需要做的就是输入，你应该马上看到这个交互式地图。

okay so the GEE map package is view upon ipy leaflet .

好的，那么GEE地图包在ipy传单上。

it's a very powerful Python library that you can create interactive map .

这是一个非常强大的Python库，您可以创建交互式地图。

but this new package is designed to what with Google's ending. 

但是这个新的软件包的设计与谷歌的结局是一致的。

so it brings all the analytical functionality of Google's engine into I pee while deflect. 

所以它把谷歌引擎的所有分析功能都带进了其中。

so and these are just realize you can use to quickly create an interactive map just.

所以你可以用这些来快速创建一个交互式地图。

today you know that the reason why I use this variable map is to be consistent with the Google's engine JavaScript API the map .

今天您知道我之所以使用这个变量映射是为了与Google的引擎JavaScript API映射保持一致。

here is the the word about using the JavaScript API so but you don't have to use the same you can sink lower case or any variable that you want we walk the same way .

这里有一个关于使用JavaScript API的单词，但是你不必使用相同的，你可以使用小写或任何你想要的变量，我们用同样的方法。

okay so I used in a pocket just to be consistent with the JavaScript API .

好吧，所以我在口袋里用了，只是为了和JavaScript API保持一致。

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mcZKT0.RptOyjYemAkBpzdPNAFpj5fPnjCPn2eAjDK8iZPxIJMZ4S1MhLq9qJnvI3WsEaEIbzl8KNMb7.ywa*gdU!/b&bo=fAczBHwHMwQDKQw!&rf=viewer_4)

and again so when you create a new map you can choose the center .

同样，当你创建一个新地图时，你可以选择中心。

so for example by d4 you can if you don't put anything you will also create the same one you will also walk using that before .

例如，通过d4，你可以，如果你不放任何东西，你也会创造同样的东西，你也会用它走路。

but you can change the center so for example can change the center too so this is the latitude and longitude and the zoom level .

但是你可以改变中心，例如，也可以改变中心，这就是经纬度和缩放级别。

so you can change this to customize these parameters as you want .

因此，您可以根据需要更改它以自定义这些参数。

okay so this month back to launch of 100 degree East.

好的，这个月回到100度东方的发射。

```python
import geemap
Map = geemap.Map(center=[40,100], zoom=4)
```

let me change it back to the US in here.

让我把它换回美国。

```python
import geemap
Map = geemap.Map(center=[40,-100], zoom=4)
```

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mcZKT0.RptOyjYemAkBpzdPPPUbZZvSw2vurGr6l4hsR4NQ1OGgsfoGWquSacboV9Xdce42*e0KqdOYU89o3fTgc!/b&bo=fQc4BH0HOAQDaUw!&rf=viewer_4)

okay so we have the pace map but if you want more pace map you can set it to that so i'ma show you like what base map is available .

好的，我们有速度图，但是如果你想要更多的速度图，你可以把它设置成这样，这样我就给你看什么样的底图是可用的。

so you can you can either go to the github page and then from here.

因此，您可以转到github页面，然后从这里。

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mcZKT0.RptOyjYemAkBpzdPNx5qGJzisMpgaozi4AGi6BuM0Lca53PZNuRDr5GVDWfDpOnpdr4bxhPlDd5v5xBTo!/b&bo=gAc4BIAHOAQDORw!&rf=viewer_4)

if you scroll up to the source code from the GE map if you click there is a Python script code base Maps .

如果您从GE地图向上滚动到源代码，如果您单击那里有一个Python脚本代码底图。

if you open this one shows you all the basement available .

如果你打开这个可以看到所有的数据库。

and all we need to do this to grab the name in here which one you like .

我们要做的就是找到你喜欢的名字。

and then copy and then I'm going to show you how to add this one to to the map .

然后复制，然后我会告诉你如何把这个添加到地图上。

and then overall they are 62 base map right now but mixed with it here at the bottom .

总的来说，它们现在是62个底图，但在底部和底图混在一起。

here I also incorporate lost base map already available in the ipy leaflet library .

在这里，我还纳入了丢失的基础地图已经在ipy传单图书馆。

so but I added some additional for example the USGS and the Navy misery and National Land cover database .

所以我增加了一些额外的数据，比如美国地质勘探局和海军灾难和国家土地覆盖数据库。

and for example also on wetlands inventory from the Fish and Wildlife Service and esri met .

例如，来自鱼类和野生动物管理局和esri的湿地调查。

so in here if you want more basement you can I'm going to talk about later.

所以在这里如果你想要更多的地下室你可以我稍后再谈。

but for now it's enough so for example if you're interested in using a Google map all we need to do we can copy this one come back to here .

但现在已经足够了，比如说，如果你对使用谷歌地图感兴趣，我们需要做的就是复制这个，回到这里。

so because this one is already interacting with everything you're doing it's you just modify this available. 

因为这个已经和你所做的一切交互了，所以你只需要修改这个。

so I'm going to map talk ed lets me so once we hit help you can show this one here.

所以我要和艾德谈谈地图，一旦我们找到帮助，你就可以在这里展示这个。

and then just at this one across prentices and then double post-roman and then out enter .

然后就在这一个穿过它，然后双后罗马，然后进入。

so here you see the new page map f it to  the map and you can turn it on and off up to you.

所以在这里你可以看到新的页面地图，你可以打开和关闭它。

so by default is also open stream it in the background here but you can add more layers .

所以默认情况下也是在后台打开它，但是你可以添加更多的层。

and also you can for example if you want to use more bassy you want the ESRI National Geographic I can copy this one back .

你也可以，例如，如果你想用更多的bassy，你想要ESRI国家地理，我可以复制这个。

here you can cut another line at let's make the top of course or enter so again you see you can it's very easy to add all the base maps in here .

在这里你可以切另一条线，让我们做顶部当然或进入，所以你再次看到你可以很容易地添加所有的底图在这里。

```python
Map.add_basemap("Esri National Geographic")
```

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mcTZMiU7*uYpmVxxffIB*boGVeZAhbdC63jiN7qC0z8VElFVcak662Kbx6Z7UFBuVeuj40YGvGcpEJL6hSMdzl7k!/b&bo=gAc4BIAHOAQDaUw!&rf=viewer_4)

and sometimes you might want to see all the base map  oh it once I also provide the saw cut that you can create is again I'm gonna show you .

有时你可能想看看所有的底图哦，一旦我也提供了锯切，你可以创建是我要再次向你展示。

for example I can create a new one could you email Oh Matt .

例如，我可以创建一个新的，你可以电子邮件哦马特。

so I'm gonna create a new map and then to show you all the basement all we want and then map top. 

所以我要创建一张新地图，然后向你展示我们想要的所有地下室，然后再绘制顶部地图。

there is a function call please me yeah it's me it's me underscore demo .

有个函数调用请告诉我是的，是我，是我。

 now you have all the base map here you can have a job down this that you can select the base map .

现在你有了所有的底图，你可以在下面做一个工作，你可以选择底图。

so first I'm going to take this one you can select any basement you like this righ now 62 basement in here no for example nao city National Land cover database.  

所以首先我要拿这个，你可以选择任何一个地下室，你喜欢这个，现在这里有62个地下室，没有，比如国家土地覆盖数据库。

and also some of the lows that does inherit from IP ID plate .

还有一些从IP标识牌继承的低点。

so for example you can change to whatever basement do you like .

比如你可以换到你喜欢的地下室。

and this is a quick way that if you want to explore some of the base map you like .

这是一个快速的方法，如果你想探索一些你喜欢的基础地图。

```python
m=geemap.Map()
m.basemap_demo()
m
```

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mcTZMiU7*uYpmVxxffIB*boGU3U3JdLWm7toZnGwVNJYBnMvY8.2qnHR0uB2GQdezo9qsTqnJvSQ3fZXo2vVLzDA!/b&bo=gAc4BIAHOAQDORw!&rf=viewer_4)

if there's any other pest map that you really like you can open an issue on the github page I can study the ED laws are to them to the source course.

如果有任何其他有害生物地图，你真的喜欢你可以打开github页上的问题，我可以研究ED的法律是他们的源代码课程。

so they you can just use keyword to add base map okay so this two ways can add basement. 

所以你可以用关键字来添加底图，好的，这两种方法可以添加底图。

but if something is not available in the package you can go online so to find other base map available using WMS or XYZ type service.

但是如果包中没有可用的内容，您可以联机，以便使用WMS或XYZ类型服务查找其他可用的底图。

so let me go back to the github page and go back to the main page from here I'll show you how to add additional base map.

所以让我回到github页面，然后回到主页，从这里我将向您展示如何添加额外的底图。

so there are two functions available in here so at WMS so WMS stands for web map service and all we need is a link andthen the name of the layer you can also add X Y Z type maps to the map so for example we can simply copy and copy this one .

所以这里有两个功能，所以在WMS，WMS代表web地图服务，我们只需要一个链接和然后图层的名称，你也可以添加X Y Z类型的地图到地图上，例如，我们可以简单地复制和复制这个。

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mca0wMYMFZnpUoqPv0hs1h7KMVdFPLjNQ9VOGg3rfgQbHSQCoj74fldIYQTJAuaKC4MHr2uVcDjmEP0LzTd3XF1Q!/b&bo=gAc4BIAHOAQDKQw!&rf=viewer_4)

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mca0wMYMFZnpUoqPv0hs1h7KN4i4i3lTCnnhLhEsTep1J6Glfga9Sh*pZOD.9NqE20FNr9RyqrK9kSmMl5StR01E!/b&bo=gAc4BIAHOAQDKQw!&rf=viewer_4)

and then come back here I'm gonna add this one to the map in here .

然后回来，我要把这个加到地图上。

so for example I can let's copy and paste this one and so basically we have the UI arrow to put a WMS map and you pass in the URL and the name of the layer .

例如，我可以复制并粘贴这个，基本上我们有一个UI箭头来放置一个WMS地图，然后你输入URL和图层的名称。

```python
import geemap
Map = geemap.Map(center=[40,-100], zoom=4)
Map.add_basemap("ROADMAP")
naip_url = 'https://basemap.nationalmap.gov/arcgis/services/USGSImageryTopo/MapServer/WMSServer?'
Map.add_wms_layer(url=naip_url, layers='0', name='USGS Imagery', format='image/png', shown=True)
Map
```

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mcTZMiU7*uYpmVxxffIB*boEwq0dHIzZZcOj9oWq6udIL8GpWeGj0coj1Xi*dG.TsPPFUYNqF.bIAB8EjtIFRQjw!/b&bo=gAc4BIAHOAQDWXw!&rf=viewer_4)

and this is the name that you want to show it on the layer control in here and also the format .

这是你想在图层控件上显示的名称，也是格式。

and we need to ship one then you add this one to the map so this is the USTA netdom is a one meter resolution .

我们需要运送一个，然后你把这个加到地图上，这是USTA网络，分辨率是一米。

```python
import geemap
Map = geemap.Map(center=[40,-100], zoom=4)
Map.add_basemap("ROADMAP")
naip_url = 'https://basemap.nationalmap.gov/arcgis/services/USGSImageryTopo/MapServer/WMSServer?'
Map.add_wms_layer(url=naip_url, layers='0', name='USGS Imagery', format='image/png', shown=True)
Map
```

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mca0wMYMFZnpUoqPv0hs1h7KIeFdExr5rwH7a2FqU12hi3QKfD7T9C9GvW6dsOyC3I62TlyPF0gBCaLVSCtO4pPE!/b&bo=gAc4BIAHOAQDaUw!&rf=viewer_4)

so you see in here it might not be very clear but I can add a new example I add mean Etna music on top of this one .

所以你在这里看到它可能不是很清楚，但我可以添加一个新的例子，我添加的意思是埃特纳音乐在此基础上。

okay so this is one way you can quickly add the base map to the GE map so that you can integrate the data with other data sources from internet without having to create one by yourself .

好的，这是一种方法，你可以快速地将基础地图添加到通用地图中，这样你就可以将数据与互联网上的其他数据源集成，而不必自己创建一个。

so if you want to find more data you can go to the source code here and you can explore some of these links .

因此，如果你想找到更多的数据，你可以到这里的源代码，你可以探索其中的一些链接。

for example if you go to the USGS national map the click link open here here shows you at hands of pace map that you can use .

例如，如果你去美国地质勘探局的国家地图点击链接打开这里显示你手中的步伐地图，你可以使用。

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mca0wMYMFZnpUoqPv0hs1h7KN4i4i3lTCnnhLhEsTep1J6Glfga9Sh*pZOD.9NqE20FEeUJsAczrrkd4nOLY3qII!/b&bo=gAc4BIAHOAQDKQw!&rf=viewer_4)

and so for example if you keep pace map right so what you are looking for is the WMS. 

例如，如果你保持正确的配速，那么你要找的是WMS。

so this one we worked directly with the IPU a leaflet or the WMS layer .

所以这个我们直接和IPU一起工作，一个传单或者WMS层。

all we need to do just for example click this one and then copy this URL from here for this portion don't copy the one after the request.

所有我们需要做的只是举例来说，点击这一个，然后从这里复制这一部分的网址不要复制请求后的一个。

those are not needed okay so you don't need this puzzle all you need to do this this one and then from here copy .

这些都不需要好吧，所以你不需要这个拼图，你需要做这个，这个，然后从这里复制。

and then come back here you can change the URL okay so from here only to change the URL it .

然后回到这里你可以改变网址好的，所以从这里只改变网址吧。

and so you can change the name of the layer but you need to make sure that you find out the name of the layer .

所以你可以改变图层的名称，但是你需要确定你找到了图层的名称。

so you can use control if in pac-man.

所以你可以在吃豆人中使用控制。

so here's showed you some of the layer within the WMS Talia.

这里展示了WMS Talia中的一些图层。

so the name is called zero so all we need to do is come back to here .

所以这个名字叫做零，所以我们要做的就是回到这里。

okay it's already zero then you can change the name for example to USD GFC merely.

好吧，它已经是零了，那么你可以把名字改成美元GFC。

```python
import geemap
Map = geemap.Map(center=[40,-100], zoom=4)
Map.add_basemap("ROADMAP")
naip_url = 'https://basemap.nationalmap.gov/arcgis/services/USGSImageryTopo/MapServer/WMSServer?'
Map.add_wms_layer(url=naip_url, layers='0', name='USGS Imagery', format='image/png', shown=True)
Map
```

![](http://m.qpic.cn/psc?/V50hD4c82V5WlK2QA7wm2c9w7l1O5BVG/45NBuzDIW489QBoVep5mca0wMYMFZnpUoqPv0hs1h7KIeFdExr5rwH7a2FqU12hi3QKfD7T9C9GvW6dsOyC3IxYOibtH9DSUaOeabOw41FY!/b&bo=gAc4BIAHOAQDaUw!&rf=viewer_4)

okay and again no sleep man then you should be able to see the new base mapping here coming into the internet map pretty nice .

好的，再次没有睡眠的人，那么你应该能够看到新的基地地图在这里进入互联网地图相当不错。

because Google is ending the JavaScript API you cannot add other base map to to the co-editor .

因为Google正在结束JavaScript API，所以您不能将其他基本映射添加到联合编辑器中。

but in here it's very flexible you can bring in all kind of a data sources from the internet .

但在这里它非常灵活，你可以从互联网上引入各种各样的数据源。

and then so you can overlay on top of other data layer data layers to explore things that you are interested in .

然后，您可以覆盖在其他数据层数据层之上，以探索您感兴趣的内容。

okay so that's all for this video.

好了，视频到此为止。

I will see you in the next one bye bye.

下次再见。










<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>SharePoint FastPack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>SharePoint FastPack</h1>
    <p>
    </p>
    <div class="confbox admonition admonition-info">
    <p>
We have recently updated the FastPack to leverage the latest features of dynaTrace and also tested it with SharePoint 2010. We also provided a package for dynaTrace 6.    </p>
    </div>
    <div class="section-2"  id="10486023_SharePointFastPack-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/10486023/icon.png" alt="images_community/download/attachments/10486023/icon.png" class="confluence-embedded-image" />
        The dynaTrace FastPack for the Microsoft SharePoint (both Windows SharePoint Services and Microsoft Office Share Server) enables faster analysis of SharePoint Applications by providing specific Sensor Packs and Dashboards to identify problems in custom WebParts, SharePoint Lists &amp; Views, usage of CAML, ...    </p>
    </div>
    <div class="section-2"  id="10486023_SharePointFastPack-FastPackDetails"  >
        <h2>FastPack Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Microsoft SharePoint FastPack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4.x, 5.x    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
SharePoint Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Tested with SharePoint 2007, 2010 and 2013    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Andreas Grabner (andreas.grabner@dynatrace.com)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community+Supported">Community Supported</a><br/>For questions:    </p>
<ul class=" "><li class=" ">    <p>
Comment on this page    </p>
</li><li class=" ">    <p>
Use the Forum <a href="https://community/display/DTFORUM/Community+Plugins+and+Extensions">Community Plugins and Extensions</a>    </p>
</li><li class=" ">    <p>
Directly contact the author    </p>
</li></ul>            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FastPack Contents    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_175734835_1_SharePointFastPack.dt60.dtp">SharePoint FastPack for dynaTrace 6.x</a>    </p>
    <p>
<a href="attachments_71073855_1_SharePointFastPack.dt41.dtp">SharePoint FastPack for dynaTrace 4.x + 5.x</a>    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/10486023/TransactionFlow.png" alt="images_community/download/attachments/10486023/TransactionFlow.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="10486023_SharePointFastPack-SharePointPerformanceDashboard"  >
        <h2>SharePoint Performance Dashboard</h2>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/10486023/PerformanceDashboard.png" alt="images_community/download/attachments/10486023/PerformanceDashboard.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
The Performance Dashboard highlights the most interesting performance aspects of a SharePoint Deployment:    </p>
<ul class=" "><li class=" ">    <p>
<i class=" ">Overall Response Time</i> shows you whether you have any general Performance Issues    </p>
</li><li class=" ">    <p>
<i class=" ">Memory and Gargabe Collection</i> allows you to see whether you need to allocate more memory for your SharePoint Application Pools or whether you have any memory leaks    </p>
</li><li class=" ">    <p>
<i class=" ">Layer Breakdown</i> gives you a quick indication on the Application Layers that are the main performance contributors, e.g: ADO.NET indicates that your SharePoint App is too heavy on the Database. ASP.NET WebParts means you want to optimize WebPart Usage.    </p>
</li><li class=" ">    <p>
<i class=" ">SharePoint WebRequests</i> shows which pages are requests, which ones have problems and which ones are fast or slow    </p>
</li><li class=" ">    <p>
<i class=" ">Critial WebParts</i> highlights those WebParts that have a high performance contribution    </p>
</li></ul>    </div>
    <div class="section-2"  id="10486023_SharePointFastPack-SharePointUsageDashboard"  >
        <h2>SharePoint Usage Dashboard</h2>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/10486023/MonitoringDashboard.png" alt="images_community/download/attachments/10486023/MonitoringDashboard.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
The Usage Dashboard helps you to understand which Lists and Views are heavily used and which ones may indicate a problem, e.g: too much load on a List results in high error rates or long response times. In order to answer these questions simply sort the View or List Response Table by Count, Failed % or Response Time.    </p>
    </div>
    <div class="section-2"  id="10486023_SharePointFastPack-PackageInformation"  >
        <h2>Package Information</h2>
    <p>
On the <strong class=" ">dynaTrace Blog</strong> the following posts give a good overview of the FastPack and give additional hints about problematic areas in SharePoint applications:    </p>
<ul class=" "><li class=" ">    <p>
<a href="http://apmblog.compuware.com/2009/04/15/dynatrace-sharepoint-package-available-on-community-portal/">dynaTrace SharePoint Fast Pack</a>    </p>
</li><li class=" ">    <p>
<a href="http://apmblog.compuware.com/2010/03/18/how-to-avoid-the-top-5-sharepoint-performance-mistakes/">5 Top Performance Problems in SharePoint</a>    </p>
</li></ul>    <p>
The Download Package includes everything you need to manage SharePoint Applications:    </p>
<ul class=" "><li class=" ">    <p>
Pre-Configured System Profile <strong class=" ">SharePoint</strong> including a Deep-Dive and Memory Sensor Group to be enabled by Developers in Pre-Prod Environments    </p>
</li><li class=" ">    <p>
2 Dashboards for Usage and Performance Monitoring    </p>
</li></ul>    </div>
    <div class="section-2"  id="10486023_SharePointFastPack-Installation"  >
        <h2>Installation</h2>
    <p>
Follow the following Steps:    </p>
<ol class=" "><li class=" ">    <p>
Import the <a href="attachments_71073855_1_SharePointFastPack.dt41.dtp">SharePoint FastPack</a> into your dynaTrace Server. For details on how to do this please refer to the <a href="https://community/display/DOCDT41/Plugin+Management">Online Documentation on Plugin Management</a>.    </p>
</li><li class=" ">    <p>
Configure your SharePoint Application Agents to use the name &quot;SharePoint&quot; using the <a href="https://community/display/DOCDT41/.NET+Agent+Configuration">.NET Agent Configuration</a> Tool on your SharePoint Servers.    </p>
</li><li class=" ">    <p>
(optional): If you also have dynaTrace UEM configure your IIS Web Server to use the name &quot;WebServer_SharePoint&quot;. More information on <a href="https://community/display/DOCDT41/Microsoft+IIS+Web+Server+Agent+Configuration">Microsoft IIS Web Server Agent Configuration</a>    </p>
</li></ol>    <p>
    </p>
    <div class="confbox admonition admonition-info">
    <p>
If you run on older versions of dynaTrace have a look at <a href="https://community/display/DL/SharePoint+FastPack+for+dynaTrace+3.x">SharePoint FastPack for dynaTrace 3.x</a>    </p>
    </div>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
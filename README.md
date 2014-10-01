<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Web Transaction Monitor Plugin</title>
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
                <h1>Web Transaction Monitor Plugin</h1>
    <div class="section-2"  id="112461052_WebTransactionMonitorPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
Allows you to execute a multi step web transaction script to be used to e.g: verify availability or functionality of critical web transactions    </p>
    <div class="confbox admonition admonition-info">
    <p>
Since dynaTrace 5.5 the Web Transaction Monitor Plugin that shipped with the product is no longer officially supported. Continued development of this plugin will be done through the Community    </p>
    </div>
    </div>
    <div class="section-2"  id="112461052_WebTransactionMonitorPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Files    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_122978362_1_com.dynatrace.diagnostics.plugins.WebTransactionMonitor_5.5.0.5226.jar">Web Transaction Monitor Plugin</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Original author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Ardeshir Arfaian    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4.2+    </p>
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
<a href="https://community/display/DL/Support+Levels">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="112461052_WebTransactionMonitorPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server via the dynaTrace Server Settings menu -&gt; Plugins -&gt; Install Plugin. For details how to do this please refer to the dynaTrace documentation:    </p>
    <p>
<a href="https://community/display/DOCDT55/Plugin+Management">Plugin Management</a>    </p>
    </div>
    <div class="section-2"  id="112461052_WebTransactionMonitorPlugin-Content"  >
        <h2>Content</h2>
<ul class="toc-indentation "><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-Overview">Overview</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-PluginDetails">Plugin Details</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-Installation">Installation</a>    </p>
</li></ul><ul class=" "><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-GomezSyntheticTransactionMonitoring">Gomez Synthetic Transaction Monitoring</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-SetupWebTransactionMonitoring">Setup Web Transaction Monitoring</a>    </p>
<ul class="toc-indentation "><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-HowtocreateaWebTransactionMonitorTask">How to create a Web Transaction Monitor Task</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-HowtoconfigureaWebTransactionMonitorTask">How to configure a Web Transaction Monitor Task</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-Youcannowconfigure%3A">You can now configure:</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-Selecthost%28s%29whichshouldbethetarget%28s%29oftheMonitor">Select host(s) which should be the target(s) of the Monitor</a>    </p>
<ul class="toc-indentation "><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-Examples">Examples</a>    </p>
</li></ul></li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-Howtocustomizetheexecutionschedule">How to customize the execution schedule</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-HowtocentrallydeployaMonitortodifferentgloballocations">How to centrally deploy a Monitor to different global locations</a>    </p>
</li></ul></li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-Usage">Usage</a>    </p>
<ul class="toc-indentation "><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-SampleScript">Sample Script</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-UseHostinyourWebTransaction">Use Host in your Web Transaction</a>    </p>
</li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-BusinessTransactionsforyourWebTransactions">Business Transactions for your Web Transactions</a>    </p>
</li></ul></li><li class=" ">    <p>
<a href="Web_Transaction_Monitor_Plugin.html#112461052_WebTransactionMonitorPlugin-KnownProblems">Known Problems</a>    </p>
</li></ul>    </div>
    <div class="section-2"  id="112461052_WebTransactionMonitorPlugin-GomezSyntheticTransactionMonitoring"  >
        <h2>Gomez Synthetic Transaction Monitoring</h2>
    <p>
Besides the Built-In Web Transaction Monitor you can also use Gomez Synthetic Transaction Monitoring: <a href="https://community/display/DOCDT55/Compuware+APM+Synthetic+Monitoring+Integration">Compuware APM Synthetic Monitoring Integration</a>    </p>
    </div>
    <div class="section-2"  id="112461052_WebTransactionMonitorPlugin-SetupWebTransactionMonitoring"  >
        <h2>Setup Web Transaction Monitoring</h2>
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-HowtocreateaWebTransactionMonitorTask"  >
        <h3>How to create a Web Transaction Monitor Task</h3>
<ol class=" "><li class=" ">    <p>
Open System Profile &gt;&gt; Preferences    </p>
</li><li class=" ">    <p>
Choose &quot;Monitors&quot; from the Configuration panel (Property Navigation)    </p>
</li><li class=" ">    <p>
Choose Create..., then select the &quot;Web Transaction Monitor&quot;    </p>
</li><li class=" ">    <p>
Rename your Web Transaction Monitor and adapt description.    </p>
</li><li class=" ">    <p>
Continue to configure the Monitor as described below.    </p>
</li></ol>    </div>
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-HowtoconfigureaWebTransactionMonitorTask"  >
        <h3>How to configure a Web Transaction Monitor Task</h3>
    <p>
If the Monitor configuration dialog is not already open, open &quot;Monitors&quot; Configuration dialog in your System Profile Preferences, select the Monitor you wish to edit and click &quot;Edit..&quot; button:    </p>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461052/wtm.png" alt="images_community/download/attachments/112461052/wtm.png" class="" />
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
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-Youcannowconfigure%3A"  >
        <h3>You can now configure:</h3>
<ol class=" "><li class=" ">    <p>
Script (see section &quot;Usage&quot;)    </p>
</li><li class=" ">    <p>
Port - you can use this setting in your script through ANT notation (see section &quot;Usage&quot;)    </p>
</li><li class=" ">    <p>
Protocol - Choose Http Version: 0.9, 1.0 or 1.1    </p>
</li><li class=" ">    <p>
Log content after errors - toggles content logging after errors. The content of the last web request will be logged if a following step produces an error. This may cause high logging volume.    </p>
</li><li class=" ">    <p>
dynaTrace Tagging - if an agent is injected into your web application, you can set this flag to receive tagged web requests and additional information in the request header (see section &quot;Usage&quot;)    </p>
</li><li class=" ">    <p>
Transaction Name (only available if tagging is enabled) - will be sent in the request header, enables dynaTrace to identify all requests belonging to this transaction    </p>
</li><li class=" ">    <p>
Transaction Location (only available if tagging is enabled) - will be sent in the request header with tag &quot;transactionLocation&quot;    </p>
</li><li class=" ">    <p>
Custom headers - allows to specify custom HTTP headers which are added to for all requests.    </p>
</li><li class=" ">    <p>
UserAgent - will be sent in the request header, enables to simulate different browsers to you website    </p>
</li><li class=" ">    <p>
UserAgentLanguage - en, de, ch, es ... test different languages supported by your website    </p>
</li><li class=" ">    <p>
Use HTTP Proxy - Choose if Web Transaction Monitor should use Http Proxy (specify host, port &amp; authentication settings if necessary)    </p>
</li><li class=" ">    <p>
Connection Timeout - time in seconds before a single request (and also the complete transaction) runs into a time out    </p>
</li><li class=" ">    <p>
Auto refresh - if selected, the Web Transaction Monitor follows redirects automatically    </p>
</li><li class=" ">    <p>
Log level - allows to increase log level of the monitor logging output    </p>
</li></ol>    </div>
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-Selecthost%28s%29whichshouldbethetarget%28s%29oftheMonitor"  >
        <h3>Select host(s) which should be the target(s) of the Monitor</h3>
    <p>
A Monitor can be configured for multiple target hosts. This means that only one configuration is necessary which is then executed for all configured machines which is especially useful in cluster environments which feature many similarly configured hosts.    </p>
    <p>
<strong class=" ">Single hosts</strong>, <strong class=" ">Host Groups</strong> or <strong class=" ">Sites</strong> are added by selecting the + icon. (You can also crate a new host if the desired host is not shown). If you add a host group or site, the monitor will be run for all contained hosts.<br/>Optionally, add an <strong class=" ">intersection</strong> of host groups or sites. The Monitor will be run for all Hosts which belong to all selected groups/sites.    </p>
    <p>
<a href="https://community/display/DOCDT50/Infrastructure">More information how to manage Hosts and Host Groups</a>    </p>
    <div class="section-4"  id="112461052_WebTransactionMonitorPlugin-Examples"  >
        <h4>Examples</h4>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Configured Hosts as shown in Hosts table    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Monitor will be run for    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Host1    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Host1    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Host1<br/>Host2    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Host1 and Host 1    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Host Group 1<br/>Host2    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
All hosts from Host Group 1 and also Host 2    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Host Group 1<br/>Host Group 2    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
All hosts from Host Group 1 and also Host Group 2    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Hosts belonging to Host Group 1, Host Group 2<br/>Host 1    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
All hosts which are <strong class=" ">both</strong> in Host Group 1 and Host Group 2 (i.e. an intersection of Host Group 1 and Host Group 2) plus Host 1    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    <div class="confbox admonition admonition-info">
    <p>
    </p>
    <p>
Even if the configuration would resolve a single Host more than once (if Host1 is also contained in Host Group 1) the Monitor is only executed once per host.    </p>
    </div>
    <p>
    </p>
    </div>
    </div>
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-Howtocustomizetheexecutionschedule"  >
        <h3>How to customize the execution schedule</h3>
    <p>
Open the <strong class=" ">Schedule</strong> tab, then choose a predefined schedule or create your own schedule if none fits. Please be aware that any Schedules which are created will be available for the whole System Profile.    </p>
    </div>
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-HowtocentrallydeployaMonitortodifferentgloballocations"  >
        <h3>How to centrally deploy a Monitor to different global locations</h3>
    <p>
Open the <strong class=" ">Schedule</strong> tab, then modify the selection of the <strong class=" ">Execute on</strong> combo box to the desired dynaTrace Collector or dynaTrace Server which will show up as <i class=" ">Embedded dynaTrace Collector</i>. Only currently connected dynaTrace Collectors are shown in this control. Please note that if a dynaTrace Collector which is connected through a slow network or a Monitor which contains larger library files is run on a remote machine, it is rarely possible that the first execution fails with a &quot;Missing Binaries&quot; error. This error should disappear on the next scheduled run of the Monitor.    </p>
    </div>
    </div>
    <div class="section-2"  id="112461052_WebTransactionMonitorPlugin-Usage"  >
        <h2>Usage</h2>
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-SampleScript"  >
        <h3>Sample Script</h3>
    <p>
A TestScript consists of a number of consecutive steps and represents the actual web transaction which should be performed. A manual with a detailed description of available steps is located under <a href="http://webtest.canoo.com/webtest/manual/manualOverview.html">Canoo WebTest Manual</a>.<br/>Here a sample TestScript:    </p>
    <div class="confbox programlisting">
                <div class="content">
        <pre><code>&lt;!-- first part --&gt;
&lt;invoke url=&quot;http://${host}:${port}/frontend/&quot; description=&quot;Home&quot;/&gt;
&lt;setInputField name=&quot;username&quot; value=&quot;demouser&quot; description=&quot;Login&quot;/&gt;
&lt;setInputField name=&quot;password&quot; value=&quot;demopass&quot; description=&quot;Login&quot;/&gt;
&lt;clickButton label=&quot;Login&quot; description=&quot;Login&quot;/&gt;
&lt;verifyText text=&quot;Welcome,&amp;amp;nbsp;demo&quot; description=&quot;Login&quot;/&gt;</code></pre>
        </div>
    </div>
    <p>
In the first part this TestScript calls GoSpace on your local machine on port 9090 (&lt;invoke&gt;), logs in with username and password (&lt;setInputField&gt;, &lt;clickButton&gt;) and verifies that the login succeeded (&lt;verifyText&gt;).    </p>
    <div class="confbox programlisting">
                <div class="content">
        <pre><code>&lt;!-- second part --&gt;
&lt;clickButton label=&quot;search&quot; description=&quot;Search&quot;/&gt;
&lt;verifyText text=&quot;Availiable space voyages of your choice&quot; description=&quot;Search&quot;/&gt;
&lt;verifyTitle text=&quot;List results&quot; description=&quot;Search&quot;/&gt;
&lt;clickLink label=&quot;Diamond Star Village&quot; description=&quot;Buy&quot;/&gt;
&lt;verifyText text=&quot;OSN-4&quot; description=&quot;Buy&quot;/&gt;
&lt;clickLink label=&quot;buy&quot; description=&quot;Buy&quot;/&gt;
&lt;clickLink label=&quot;I agree to the GoSpace license terms&quot; description=&quot;Agree&quot;/&gt;
&lt;verifyText text=&quot;Thank you for booking your voyage with GoSpace&quot; description=&quot;Agree&quot;/&gt;</code></pre>
        </div>
    </div>
    <p>
In the second part a search is performed (&lt;clickButton&gt;), the success of the search is verified (&lt;verifyText&gt;, &lt;verifyTitle&gt;), a travel selected (&lt;clickLink&gt;), verified(&lt;verifyText&gt;) and bought (&lt;clickLink&gt;). Next the success of the purchase is verified (&lt;verifyText&gt;).    </p>
    <div class="confbox programlisting">
                <div class="content">
        <pre><code>&lt;!-- third part --&gt;
&lt;clickLink label=&quot;last minute&quot; description=&quot;LastMinute&quot;/&gt;
&lt;sleep seconds=&quot;2&quot; description=&quot;LastMinute&quot;/&gt;
&lt;clickLink label=&quot;logout&quot; description=&quot;Logout&quot;/&gt;</code></pre>
        </div>
    </div>
    <p>
In the third part of this TestScript a last minute search is performed followed by thinktime (&lt;sleep&gt;) and a logout (&lt;clickLink&gt;).    </p>
    </div>
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-UseHostinyourWebTransaction"  >
        <h3>Use Host in your Web Transaction</h3>
    <p>
The host can be set statically in the script but it is recommended to use they syntax ${host} to allow the script to be run on multiple target hosts.    </p>
    <div class="confbox programlisting">
                <div class="content">
        <pre><code>&lt;invoke url=&quot;http://${host}:${port}/frontend/&quot; description=&quot;GoSpace home&quot; /&gt;</code></pre>
        </div>
    </div>
    <p>
Following TestScripts are provided:<br/><a href="attachments_114329112_1_GoSpaceTransaction.txt">GoSpace only Web Transaction</a> (configure port: 9090, runs login, query &amp; buy, last minute search, logout)<br/><a href="attachments_114329080_1_GospaceSearchTestscript.txt">GoSpace only Web Transaction 2</a> (configure port: 9090, runs login, query from random departure spaceport, logout)<br/><a href="attachments_114329083_1_DotNetPayTransaction.txt">DotNetPay only Web Transaction</a> (configure port: 9082, runs login, available cash, depending on available cash: transfer or recharge bank deposit)<br/><a href="attachments_114329108_1_GoSpaceDotNetPayTransaction.txt">GoSpace and DotNetPay Web Transaction</a> (configure port: 9090, runs login, query &amp; buy, last minute search &amp; direct buy, check if direct buy successful: recharge bank deposit )<br/><strong class=" ">Timer Name </strong><br/>Add the timer name for each step by using the description attribute:    </p>
    <div class="confbox programlisting">
                <div class="content">
        <pre><code>&lt; ...  description=&quot;Timer Name&quot;/&gt;</code></pre>
        </div>
    </div>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461052/tagged2.png" alt="images_community/download/attachments/112461052/tagged2.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461052/tagged.png" alt="images_community/download/attachments/112461052/tagged.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
<strong class=" ">Better simulate browser behaviour...</strong><br/>...download all referenced content such as css, images, flash &amp; javascript content.<br/><i class=" ">See Canoo WebTest step &bdquo;verifyLinkedContent&quot;</i><br/><i class=" ">See Canoo WebTest step &bdquo;verifyImages&quot;</i><br/><br/>Without any of these steps the WTAMonitor only requests what it needs:<br/><i class=" ">basically the url's in the script</i><br/><i class=" ">.js files if needed for button clicks,...</i><br/><i class=" ">no additional ressources (images, css, ...)</i>    </p>
    </div>
    <div class="section-3"  id="112461052_WebTransactionMonitorPlugin-BusinessTransactionsforyourWebTransactions"  >
        <h3>Business Transactions for your Web Transactions</h3>
    <p>
Make sure &quot;dynaTrace Tagging&quot; is enabled in your Web Transaction Monitor settings<br/>Define Business Transactions to filter and group PurePaths by transaction name and monitor which generated them:<br/>To measure this requests headers you have to configure them in the Servlet Sensor Pack:    </p>
<ol class=" "><li class=" ">    <p>
Open System Profile &gt;&gt; Preferences &gt;&gt; Open Agent Group &gt;&gt; Sensor Configuration    </p>
</li><li class=" ">    <p>
Select &quot;Properties..&quot; of Servlet Sensor and adjust as shown on the screenshot    </p>
</li><li class=" ">    <p>
Open System Profile &gt;&gt; Preferences &gt;&gt; Measures &gt;&gt; Add Measure... &gt;&gt; Business Transaction Evaluation/Filter/Grouping Values &gt;&gt; Web Request - Header value    </p>
</li><li class=" ">    <p>
Configure the header field as shown in screenshot    </p>
</li></ol>    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461052/sensor.png" alt="images_community/download/attachments/112461052/sensor.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461052/measure.png" alt="images_community/download/attachments/112461052/measure.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
Create the Business Transaction:    </p>
<ol class=" "><li class=" ">    <p>
Open System Profile &gt;&gt; Preferences &gt;&gt; Business Transactions &gt;&gt; Create ..    </p>
</li><li class=" ">    <p>
Enter a Name    </p>
</li><li class=" ">    <p>
Select an Evaluation Criteria, for example Pure Path duration    </p>
</li><li class=" ">    <p>
Select the just created Measure as Grouping Criteria.    </p>
</li></ol>    </div>
    </div>
    <div class="section-2"  id="112461052_WebTransactionMonitorPlugin-KnownProblems"  >
        <h2>Known Problems</h2>
    <p>
As a matter of deployment size, following functionality has been excluded (which is usually included in Canoo WebTest):    </p>
<ul class=" "><li class=" ">    <p>
Groovy Support (extension step groovy)    </p>
</li><li class=" ">    <p>
Filter Steps are disabled    </p>
</li><li class=" ">    <p>
PDF Steps are disabled    </p>
</li><li class=" ">    <p>
Excel Steps are disabled    </p>
</li><li class=" ">    <p>
Email Steps are disabled    </p>
</li></ul>    <p>
    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
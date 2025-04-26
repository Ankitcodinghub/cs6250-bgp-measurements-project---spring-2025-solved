# cs6250-bgp-measurements-project---spring-2025-solved


    

**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** [CS6250 BGP Measurements Project – Spring 2025 Solved](https://www.ankitcodinghub.com/product/cs6250-bgp-measurements-project-spring-2025-solved/)

    📩 **If you need this solution or have special requests:**  
    **Email:** ankitcoding@gmail.com  
    📱 **WhatsApp:** +1 419 877 7882  
    📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

    *We deliver fast, professional, and affordable academic help.*

    ---

    <h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;132806&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6250 BGP Measurements Project – Spring 2025 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Please respect the intellectual ownership of course materials. This is solely for current CS6250 students. The Honor Code strictly forbids public posting of the material contained within.

Table of Contents

<h1><a name="_Toc18822"></a>Motivation</h1>
In this assignment, we will explore Internet Measurements, a field of Computer Networks which focuses on large scale data collection systems and techniques that provide us with valuable insights and help us understand (and troubleshoot) how the Internet works. There are multiple systems and techniques that focus on DNS measurements, BGP measurements, topology measurements, etc. There are multiple conferences in this area, which we invite you to explore and keep up with the papers that are published. The IMC conference is one of the flagship conferences in this area: <a href="https://conferences.sigcomm.org/imc/2022/">ACM Internet Measurement Conference</a>

&nbsp;

A gentle introduction into the Internet Measurement field is to work with large scale BGP measurements and data to study topics such as:

<ul>
<li>Characterizing growth of the Internet using various measures, such as number of advertised prefixes, the number of Autonomous Systems, the percentage growth of prefixes advertised by Autonomous System, and the dynamics of Autonomous System path lengths</li>
<li>Inferring problems related to short-lived Announcement and Withdrawals,</li>
<li>Inferring possible DDoS attacks by identifying community countermeasures such as “Remote Triggered Blackholing”</li>
</ul>
<h1><a name="_Toc18823"></a>Introduction</h1>
In this project we will use the <a href="https://bgpstream.caida.org/">BGPStream</a> tool and its Python interface <a href="https://bgpstream.caida.org/docs/api/pybgpstream">PyBGPStream</a> to understand the BGP protocol and interact with BGP data. The goal is to gain a better understanding of BGP and to experience how researchers, practitioners, and engineers have been using BGPStream to gain insight into the dynamics of the Internet. If you are interested in going deeper, you can use these same tools to observe and analyze real-time BGP data or download and analyze other historical BGP data.

&nbsp;

<h1><a name="_Toc18824"></a>Project Overview and Background</h1>
The zip file accompanying this assignment contains the code and data needed to implement the&nbsp; functions in the file <strong>bgpm.py</strong>. You will submit only <strong>bgpm.py</strong> to Gradescope and all your code for the project must be contained within <strong>bgpm.py</strong>.

&nbsp;

This project description, in combination with the comments in <strong>bgpm.py</strong>, comprise the complete requirements for the project. There are two complete sets of data included in the zip file and the provided test harness in <strong>check_solution.py</strong> will test each of your functions against both sets of data. You are welcome to copy and modify <strong>check_solution.py</strong> to better suit your development and debugging workflow, but you will have the best chance of success with the hidden data set used for grading if your final submission passes all the tests in the unmodified <strong>check_solution.py</strong>.

&nbsp;

<strong>This project is designed to work in the class VM where the BGPStream libraries are installed. </strong>

<strong>Your code will need to run without modification in the course VM.</strong>

&nbsp;

Some of the functions will have runtimes of several minutes. There is a lot of data to process, so the best way to speed up those functions is by focusing on the efficiency of your implementation. It is possible, but not supported, to install BGPStream and PyBGPStream on your local machine. Please don’t ask TA staff for help if you decide to do this. <strong>Gradescope imposes a hard time limit of 40 minutes for a grading session. We have no control over this and will not be able to make any allowances if your submission does not complete within that time limit. </strong>

&nbsp;

<h2><a name="_Toc18825"></a>Required Background</h2>
For this project, we will be using <a href="https://bgpstream.caida.org/">BGPStream</a><a href="https://bgpstream.caida.org/">,</a> an <em>open-source software framework for live and historical BGP data analysis, supporting scientific research, operational monitoring, and postevent analysis</em>. BGPStream and <a href="https://bgpstream.caida.org/docs/api/pybgpstream">PyBGPStream</a> are maintained by the <a href="https://www.caida.org/">Center for Applied Internet</a> <a href="https://www.caida.org/">Data Analysis</a> (CAIDA).

&nbsp;

<h2><a name="_Toc18826"></a>Read the resources</h2>
A high-level overview about how the BGPStream tool was developed was published by CAIDA in <a href="https://dl.acm.org/doi/pdf/10.1145/2987443.2987482"><em>BGPStream: A Software Framework for Live and Historical BGP Data Analysis</em></a><a href="https://dl.acm.org/doi/pdf/10.1145/2987443.2987482">.</a> This paper provides useful background and practical examples using BGPStream, so be sure to read it. Additionally, you should read <a href="https://web.archive.org/web/20230925075043/https:/afrinic.net/blog/327-on-the-african-peering-connectivity-revealable-via-bgp-route-collectors"><em>African peering connectivity revealed via BGP route collectors</em></a><a href="https://web.archive.org/web/20230925075043/https:/afrinic.net/blog/327-on-the-african-peering-connectivity-revealable-via-bgp-route-collectors">,</a> which provides a practical illustration of how the BGP collection system works.

<h2><a name="_Toc18827"></a>Run Example Code Snippets</h2>
All the tasks are to be implemented using the Python interface to BGPStream. You are strongly encouraged to browse the following resources to familiarize yourself with the tool, and to run the example code snippets:

<ul>
<li>PyBGPStream API: <a href="https://bgpstream.caida.org/docs/api/pybgpstream">https://bgpstream.caida.org/docs/api/pybgpstream</a></li>
<li>PyBGPStream API Tutorial: <a href="https://bgpstream.caida.org/docs/tutorials/pybgpstream">https://bgpstream.caida.org/docs/tutorials/pybgpstream</a></li>
<li>PyBGPStream Repository: <a href="https://github.com/CAIDA/pybgpstream">https://github.com/CAIDA/pybgpstream</a></li>
<li>Official Examples: <a href="https://github.com/CAIDA/pybgpstream/tree/master/examples">https://github.com/CAIDA/pybgpstream/tree/master/examples</a></li>
</ul>
<h2><a name="_Toc18828"></a>Important Note</h2>
As will become apparent when you peruse the above documentation and tutorial information, the majority of BGPStream use cases involve gathering data – either live or historical – directly from the Route Collectors (which we refer to simply as “collectors”). The code for accessing a collector or set of collectors directly usually looks like this:

&nbsp;

stream = pybgpstream.BGPStream(&nbsp;&nbsp;&nbsp;&nbsp; record_type=”updates”,&nbsp;&nbsp;&nbsp;&nbsp; from_time=”2017-07-07 00:00:00″,&nbsp;&nbsp;&nbsp;&nbsp; until_time=”2017-07-07 00:10:00 UTC”,&nbsp;&nbsp;&nbsp;&nbsp; collectors=[“route-views.sg”, “route-views.eqix”],&nbsp;&nbsp;&nbsp;&nbsp; filter=”peer 11666 and prefix more 210.180.0.0/16″

)

&nbsp;

Each of the parameters to <strong>pybgpstream.BGPStream()</strong> winnows the data retrieved from the collector(s). <strong>Because we are using pre-cached historical data in this project, you will not need to specify a collector or a time range. You also don’t need to use any additional filtering.</strong>

For this project, you can use set up and configure your streams with:

&nbsp;

stream = pybgpstream.BGPStream(data_interface=”singlefile”) stream.set_data_interface_option(“singlefile”, type, fpath)

&nbsp;

where <strong>type</strong> is one of <strong>[“rib-file”, “upd-file”]<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a></strong> and <strong>fpath</strong> is a string representing the path to a specific cache file. When processing multiple files, you will create one stream per file.

&nbsp;

<h2><a name="_Toc18829"></a>Familiarize Yourself with the BGP Record Format and BGP Attributes</h2>
It is critical that you understand the BGP record format, especially the meaning and content of the fields (data attributes). A detailed explanation of BGP records and attributes can be found in <a href="https://www.rfc-editor.org/rfc/rfc4271.txt">RFC 4271: A Border Gateway Protocol 4 (BGP</a><a href="https://www.rfc-editor.org/rfc/rfc4271.txt">–</a><a href="https://www.rfc-editor.org/rfc/rfc4271.txt">4)</a><a href="https://www.rfc-editor.org/rfc/rfc4271.txt">.</a>

It’s also worth spending some time exploring the provided data using the <a href="https://bgpstream.caida.org/docs/tools/bgpreader">BGPReader</a> command line tool (“<em>a command line tool that prints to standard output information about the BGP records and the BGP elems that are part of a BGP stream</em>”). Doing so will be particularly helpful in understanding how the fields described in RFC 4271 and elsewhere map to the <em>BGP record</em> and <em>BGP elem</em> concepts used by BGPStream and PyBGPStream.

Because PyBGPStream allows you to extract the BGP attributes from BGP records using code, you <strong><em><u>will not</u></em></strong> have to interact with the BGP records in this format, but it is, nevertheless, helpful to see some examples using BGPReader to understand the fields. The next section shows

Here, we will show sample command line output from BGPReader for <strong><em><u>illustration</u></em></strong> purposes:

# read records from an update file, filtering for IPv4 only <strong>bgpreader -e –data-interface singlefile –data-interface-option \ upd-file=./rrc04/update_files/ris.rrc04.updates.1609476900.300.cache \ </strong>

<strong>–filter ‘ipv 4’ </strong>

<strong>&nbsp;</strong>

# read records from a rib file, filtering for IPv4 only <strong>bgpreader -e –data-interface singlefile –data-interface-option \ rib-file=./rrc04/rib_files/ris.rrc04.ribs.1262332740.120.cache \ –filter ‘ipv 4’</strong>

&nbsp;

<h2><a name="_Toc18830"></a>Update Example</h2>
The box below contains an example of an update record. In the record, the “|” character separates different fields. In yellow we have highlighted the <strong>type </strong>(A stands for Advertisement), the <strong>advertised prefix</strong> (210.180.224.0/19), <strong>the path</strong> (11666 3356 3786), and the <strong>origin AS </strong>(3786).

<table width="624">
<tbody>
<tr>
<td width="624">update|A|1499385779.000000|routeviews|routeviews.eqix|None|None|11666|206.126.236.24|210.180.224.0/19|206. 126.236.24|11666 3356 3786|11666:1000 3356:3 3356:2003 3356:575

3786:0 3356:22 11666:1002 3356:666 3356:86|None|None
</td>
</tr>
</tbody>
</table>
&nbsp;

<h2><a name="_Toc18831"></a>RIB Example</h2>
The following is a Routing Information Base (RIB) record example. Consecutive “|” characters indicate fields without data.

R|R|1445306400.000000|routeviews|route-

views.sfmix|||32354|206.197.187.5|1.0.0.0/24|206.197.187.5|3235 4 15169|15169|||

&nbsp;

&nbsp;

&nbsp;

&nbsp;

<h1><a name="_Toc18832"></a>Setup</h1>
<strong>Do not rely on the directory layout of the provided data</strong>. Gradescope does not mirror the directory layout from the provided files. Specifically, in your final submission, do not directly access the filesystem in any way and do not import all or part of either <strong>os</strong> or <strong>pathlib</strong>. All filesystem interaction will occur via PyBGPStream and the file paths will be taken from the Python list in the parameter named <strong>cache_files</strong> that is passed to each function.

&nbsp;

<h2><a name="_Toc18833"></a>Cache Files / Snapshots</h2>
Locate the directory <strong>rrc04/rib_files</strong> included with this assignment. This directory contains RIB dump files. Each filename (e.g., <strong>ris.rrc04.ribs.1262332740.120.cache</strong>) includes&nbsp; the collector’s name (<strong>ris.rrc04</strong>), the type of data (<strong>ribs</strong>), and the <a href="https://www.epochconverter.com/">Unix</a> <a href="https://www.unixtimestamp.com/">timestamp</a> of the data (<strong>1262332740</strong>, which you can convert to a date via either of the two above links).

&nbsp;

Each of the cache files is a snapshot of BGPM data collected by the collector at the time of the timestamp. In the rest of this assignment the term “snapshot” refers to the data in a particular cache file. <strong><em><u>Do not pull your own data</u></em></strong>. Your solution will be graded using cached data only.

&nbsp;

You will need to write code to process the cache files. Each entry in <strong>cache_files</strong> is a string containing the full path to a cache file. To access a given path, your code will need to set up the appropriate data interface in your <strong>BGPStream()</strong> constructor:

stream = pybgpstream.BGPStream(data_interface=”singlefile”) stream.set_data_interface_option(“singlefile”, type, fpath)

&nbsp;

where <strong>type</strong> is one of <strong>[“rib-file”, “upd-file”]</strong> and <strong>fpath</strong> is a string representing the path to a specific cache file. When processing multiple files, you will create one stream per file.

<strong>Tip:</strong> Your code shouldn’t make assumptions about the number of cache files.

&nbsp;

<h1><a name="_Toc18834"></a>Task 1. Understanding BGP Routing table Growth</h1>
In this task you will measure the growth over time of Autonomous Systems and advertised prefixes. The growth of unique prefixes contributes to ever-growing routing tables handled by routers in the Internet core. As optional background reading, please read the seminal paper <a href="https://www.cs.utexas.edu/users/lam/395t/papers/BGP_table_growth2004.pdf"><em>On</em></a> <a href="https://www.cs.utexas.edu/users/lam/395t/papers/BGP_table_growth2004.pdf"><em>Characterizing BGP Routing Table Growth</em></a><a href="https://www.cs.utexas.edu/users/lam/395t/papers/BGP_table_growth2004.pdf">.</a>

&nbsp;

<h2><a name="_Toc18835"></a>Task 1A: Unique Advertised Prefixes Over Time</h2>
This task will use cache files from the <strong>rib_files</strong> subdirectories. These are RIB files, so you will pass “rib-file” in your call to <strong>set_data_interface_option()</strong>. Using the data from cache files, measure the number of <strong>unique advertised prefixes over time</strong>. Each file is an annual snapshot. Calculate the number of unique prefixes within each snapshot by completing the function <strong>unique_prefixes_by_snapshot()</strong>. Make sure that your function returns the data structure exactly as specified in <strong>bgpm.py</strong>.

&nbsp;

<h2><a name="_Toc18836"></a>Task 1B: Unique Autonomous Systems Over Time</h2>
This task will use cache files from the <strong>rib_files</strong> subdirectories. These are RIB files, so you will pass “rib-file” in your call to <strong>set_data_interface_option()</strong>. Using the data from the cache files, measure the number of <strong>unique Autonomous Systems over time</strong>. Each file is an annual snapshot. Calculate the number of unique ASes within each snapshot by completing the function <strong>unique_ases_by_snapshot()</strong>. Make sure that your function returns the data structure exactly as specified in <strong>bgpm.py</strong>.

&nbsp;

Note: Consider all paths in each snapshot. Here, we consider all AS that appear in the paths (not only the origin AS). You may encounter corner cases of paths with the following form: “25152 2914 18687 {7829,14265}”. In this case, consider the AS in the brackets as a single AS. So, in this example, you will count 4 distinct ASes.

&nbsp;

<h2><a name="_Toc18837"></a>Task 1C: Top-10 Origin AS by Prefix Growth</h2>
This task will use cache files from the <strong>rib_files</strong> subdirectories. These are RIB files, so you will pass “rib-file” in your call to <strong>set_data_interface_option()</strong>. Using the data from the cache files, calculate the percentage growth in advertised prefixes for each AS over the entire timespan represented &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; by &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; the snapshots &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; by &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; completing &nbsp;&nbsp;&nbsp;&nbsp; the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; function <strong>top_10_ases_by_prefix_growth()</strong>. Make sure that your function returns the data structure exactly as specified in <strong>bgpm.py</strong>.

&nbsp;

Consider each origin AS separately and measure the growth of the total unique prefixes advertised by that AS from its first appearance to its last appearance. To compute this, for each origin AS:

<ol>
<li>Identify the snapshots where the origin AS first appears and last appears in the dataset. <strong>Note:</strong> An AS is <strong>not</strong> guaranteed to appear in every snapshot, nor it is guaranteed to</li>
</ol>
appear in the first and last snapshots.

<ol start="2">
<li>Calculate the percentage increase of the advertised prefixes, using the identified first and the last snapshot appearances. For example, assuming 5 given cache files, let’s say AS X first appeared in the 2<sup>nd</sup> snapshot and last appeared in the 4<sup>th</sup> and advertised the following number of prefixes:</li>
</ol>
[0, 124, 215, 512, 0] The percentage increase would then be:

= 3.13 or 313%

<ol start="3">
<li>Report the top 10 origin AS that experienced the largest growth, and sort those from smallest to largest.</li>
</ol>
<strong>Note:</strong> There are no ties, so don’t worry about implementing tie-breaking.

&nbsp;

Edge case: When calculating the prefixes originating from an origin AS, you may encounter paths of the following form: “25152 2914 18687 {7829,14265}”. This is an edge case, and it should affect only a small number of prefixes. In this case, you consider the entire set of AS “{7829,14265}” as the origin AS.

<h1><a name="_Toc18838"></a>Task 2: Routing Table Growth: AS-Path Length Evolution Over Time</h1>
In this task you will measure if an AS is reachable over longer or shorter path lengths as time progresses. Towards this goal you will measure the AS path lengths, and how they evolve over time.

This task will use cache files from the <strong>rib_files</strong> subdirectories. These are RIB files, so you will pass “rib-file” in your call to <strong>set_data_interface_option()</strong>. Using the data from the cache files, calculate the shortest path for each origin AS in each snapshot by completing the function <strong>shortest_path_by_origin_by_snapshot()</strong>. Make sure that your function returns the data structure exactly as specified in <strong>bgpm.py</strong>.

For each snapshot, you will compute the shortest AS path length for each origin AS in the snapshot by following the steps below:

<ul>
<li>Identify each origin AS present in the snapshot. For example, given the path “11666 3356 3786”, “3786” is the origin AS.</li>
<li>For each origin AS, identify all the paths for which it appears as the origin AS.</li>
<li>Compute the length of each path by considering each AS in the path only once. In other words, you want to remove the duplicate entries for the same AS in the same path and count the total number of unique AS in the path.</li>
<li><strong><em><u>Example</u></em>:</strong> Given the path “25152 2914 3786 2914 18313”, ”18313” is the origin</li>
</ul>
AS and ”2914” appears twice in the path. This is a path of length 4.

<ul>
<li>Among all the paths for an AS within the snapshot, compute the shortest path length.</li>
<li>Filter out all paths of length 1.</li>
<li><strong><em><u>Corner cases</u></em>:</strong> The data that we are working with are real data, which means that there may be <strong><em>few</em></strong> corner cases. In the vast majority of cases, paths have a straightforward form of “25152 2914 3786”, but you might encounter corner cases such as:
<ol>
<li>If an AS path has a single unique AS or a single repeated AS (e.g., “25152</li>
</ol>
</li>
</ul>
25152 25152”), the path has length 1 and should be ignored

<ol start="4271">
<li>An AS path entry that looks like “{2914,14265}” is an aggregate or AS_SET and constitutes a single AS path entry. It does not need to be parsed in any way. You can read more about aggregation in <a href="https://www.rfc-editor.org/rfc/rfc4271.txt">RFC 4271</a><a href="https://www.rfc-editor.org/rfc/rfc4271.txt">.</a></li>
</ol>
<strong><em><u>Example</u></em></strong>: The length of the AS path “25152 2914 18687 {2914,14265} 2945 18699” is 6.

<strong><em><u>Example</u></em></strong>: The length of the AS path “25152 2914 18687 18687 {18687}” is 4. The entries “18687” and “{18687}” are distinct, so you only deduplicate “18687”.

<ol>
<li>You can ignore all other corner cases.</li>
</ol>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<h1><a name="_Toc18839"></a>Task 3: Announcement-Withdrawal Event Durations</h1>
In this task, we will measure how long prefix Announcements last before they are withdrawn. This matters because, when a prefix gets Advertised and then Withdrawn, this information propagates and affects the volume of the associated BGP traffic. Optional background reading on this topic can be found in <a href="https://labs.ripe.net/author/vastur/the-shape-of-a-bgp-update/"><em>The Shape of a BGP Update</em></a><a href="https://labs.ripe.net/author/vastur/the-shape-of-a-bgp-update/">.</a>

&nbsp;

This task will use cache files from the <strong>update_files</strong> subdirectories. These are update files, so you will pass “upd-file” in your call to <strong>set_data_interface_option()</strong>. Using the data from the cache files, we will measure how long prefix Announcements last before they are withdrawn by completing the function <strong>aw_event_durations()</strong>. Make sure that your function returns the data structure exactly as specified in <strong>bgpm.py</strong>.

&nbsp;

In defining Announcement Withdrawal (AW) events, we will only consider <strong><em>explicit withdrawals</em></strong>. An explicit withdrawal occurs when a prefix is advertised with an (<strong>A</strong>)nnouncement and is then (<strong>W</strong>)ithdrawn. In contrast, an implicit withdrawal occurs when a prefix is advertised (A) and then re-advertised (A) – usually with different BGP attributes.

&nbsp;

To compute the duration of an Explicit AW event for a given peerIP/prefix, you will need to monitor the stream of (<strong>A</strong>)nnouncements and (<strong>W</strong>)ithdrawals separately per peerIP/prefix pair.

&nbsp;

<ul>
<li><strong><em><u>Example</u></em></strong>: Given the stream: A1 A2 A3 W1 W2 W3 W4 for a specific peerIP/prefix pair, you have an implicit withdrawal A1-A2, another implicit withdrawal A2-A3, and, finally, an <strong>explicit withdrawal (and AW event) A3-W1</strong>. W1-W2, W2-W3, and W3-W4 are all meaningless, as there’s no active advertisement. The duration of the AW event is the time difference between A3 and W1. Again, we are only looking for <strong>last A and first W.</strong></li>
<li><strong><em><u>Example</u></em></strong>: Given the stream: A1 A2 A3 W1 W2 W3 W4 A4 A5 W4 for a specific peerIP/prefix pair, we have two AW events at A3-W1 and A5-W4.</li>
<li>We consider only non-zero AW durations.</li>
</ul>
<h1><a name="_Toc18840"></a>Task 4: RTBH Event Durations</h1>
In this task you will identify and measure the duration of Real-Time Blackholing (RTBH) events.

&nbsp;

You will need to become familiar with Blackholing events. Good resources for this include <a href="https://datatracker.ietf.org/doc/html/rfc7999#section-2"><em>RFC</em></a>

<a href="https://datatracker.ietf.org/doc/html/rfc7999#section-2"><em>7999, Section 2</em></a><a href="https://datatracker.ietf.org/doc/html/rfc7999#section-2">,</a> <a href="https://blog.apnic.net/2019/03/22/bgp-communities-a-weapon-for-the-internet-part-2/"><em>BGP communities: A weapon for the Internet (Part 2)</em></a><a href="https://blog.apnic.net/2019/03/22/bgp-communities-a-weapon-for-the-internet-part-2/">,</a> and the video <a href="https://www.youtube.com/watch?v=ot4QUqgunBc"><em>Nokia </em></a><a href="https://www.youtube.com/watch?v=ot4QUqgunBc"><em>–</em></a> <a href="https://www.youtube.com/watch?v=ot4QUqgunBc"><em>SROS: RTBH </em></a><a href="https://www.youtube.com/watch?v=ot4QUqgunBc"><em>– </em></a><a href="https://www.youtube.com/watch?v=ot4QUqgunBc"><em>Blackhole Community</em></a><a href="https://www.youtube.com/watch?v=ot4QUqgunBc">.</a>

&nbsp;

This task will use cache files from the <strong>update_files_blackholing</strong> subdirectories. These are update files, so you will pass “upd-file” in your call to <strong>set_data_interface_option()</strong>.

Using the data from the cache files, we will identify events where prefixes are tagged with a Remote Triggered Blackholing (RTBH) community and measure the time duration of the RTBH events by completing the function <strong>rtbh_event_durations()</strong>. Make sure that your function returns the data structure exactly as specified in <strong>bgpm.py</strong>.

&nbsp;

The duration of an RTBH event for a given peerIP/prefix pair is the time elapsed between the last (<strong>A</strong>)nnouncement of the peerIP/prefix that is tagged with an RTBH community value and the first (<strong>W</strong>)ithdrawal of the peerIP/prefix. In other words, we are looking at the stream of Announcements and Withdrawals for a given peerIP/prefix and identifying only <strong>explicit withdrawals</strong> for an RTBH tagged peerIP/prefix.

&nbsp;

To identify and compute the duration of an RTBH event for a given peerIP/prefix, you will need to monitor the stream of (<strong>A</strong>)nnouncements and (<strong>W</strong>)ithdrawals separately per peerIP/prefix pair.

&nbsp;

<ul>
<li><strong><em>Example</em></strong>: Given the stream: A1 A2 A3(RTBH) A4(RTBH) W1 W2 W3 W4 for a specific peerIP/prefix pair, A4(RTBH)-W1 denotes an RTBH event and the duration is calculated by taking the time difference between A4(RTBH) and W1.</li>
<li><strong><em>Note</em></strong>: There can be more than one RTBH event in a given stream. For example, in the stream A1 A2 A3(RTBH) A4(RTBH) W1 W2 W3 W4 A5(RTBH) W5, there are two RTBH events: A4(RTBH)-W1 and A5(RTBH)-W5.</li>
<li><strong><em>Example</em></strong>: Given the stream A1 A2 A3(RTBH) A4 A5 W1 W2 for a specific peerIP/prefix pair, the announcement A3(RTBH) followed by A4 is an implicit withdrawal. There is no explicit withdrawal and, thus, no RTBH event.</li>
<li>In case of duplicate announcements, use the latest.</li>
<li>Consider only non-zero duration events.</li>
</ul>
&nbsp;

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<h1><a name="_Toc18841"></a>Submission</h1>
Submit <strong>bgpm.py</strong> to Gradescope.

&nbsp;

<h1><a name="_Toc18843"></a>Honor Code / Academic Integrity / Plagiarism</h1>
Please refer to the Georgia Tech Honor Code located here:

<a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">https://policylibrary.gatech.edu/student</a><a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">–</a><a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">affairs/academic</a><a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">–</a><a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">honor</a><a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">–</a><a href="https://policylibrary.gatech.edu/student-affairs/academic-honor-code">code</a>

&nbsp;

We strictly enforce Section 3. Student Responsibilities including these prohibited actions:

<ul>
<li>Unauthorized Access: Possessing, using, or exchanging improperly acquired written or verbal information in the preparation of a problem set, laboratory report, essay, examination, or other academic assignment.</li>
<li>Unauthorized Collaboration: Unauthorized interaction with another Student or Students in the fulfillment of academic requirements.</li>
<li>Plagiarism: Submission of material that is wholly or substantially identical to that created or published by another person or persons, without adequate credit notations indicating the authorship.</li>
<li>False Claims of Performance: False claims for work that has been submitted by a Student.</li>
</ul>
&nbsp;

In addition, the usage of AI tools such as ChatGPT in assisting and/or completing part or all of your project is <strong>explicitly prohibited</strong>. Even if they are used for just one task, that constitutes an academic integrity violation and you will receive a 0 for the <strong>entire project</strong>.

&nbsp;

The same holds true if you are found to have accessed and utilized external resources such as non-CAIDA GitHub repositories containing partial or complete solutions, other student solutions (past or present), or solutions uploaded to sites like CourseHero. Even if said resources are used for just one task, that constitutes an academic integrity violation and you will receive a 0 for the <strong>entire project</strong>.

&nbsp;

Official resources and those referenced in the project document such as the official Python documentation, official CAIDA documentation, code examples, repositories, etc. do not need to be cited. If you reference unofficial coding/programming resources such as W3Schools, Stack Overflow, etc. <strong>please cite them in your code. </strong>

&nbsp;

If you are struggling with certain tasks, ask for help from your peers and/or the teaching staff on Ed Stem, come to office hours, and if all else fails, move on to other tasks so you can at least get partial points on the project. That is far better than receiving a 0 for the entire project due to an academic integrity violation.

<a href="#_ftnref1" name="_ftn1">[1]</a> You can see a complete list of types by running: <strong>bgpreader –data-interface singlefile -o?</strong>
    

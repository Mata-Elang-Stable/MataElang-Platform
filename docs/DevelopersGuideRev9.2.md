<h1>
  <span>Developer Guide</span>
</h1>
<h2 id="h.30j0zll">
  <span>Mata Elang Intrusion Detection System</span>
</h2>
<h2><span>Table of Contents</span></h2>
<p>
  <span><a href="#h.4i7ojhp">Overview of Mata
      Elang</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.4i7ojhp">3</a></span>
</p>
<p>
  <span><a href="#h.2xcytpi">Mata Elang</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.2xcytpi">3</a></span>
</p>
<p>
  <span><a href="#h.1ci93xb">Mata Elang
      Community</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.1ci93xb">3</a></span>
</p>
<p>
  <span><a href="#h.3whwml4">System
      Architecture</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.3whwml4">4</a></span>
</p>
<p>
  <span><a href="#h.2bn6wsx">Data Source</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.2bn6wsx">5</a></span>
</p>
<p>
  <span><a href="#h.qsh70q">Defense
      Center</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.qsh70q">5</a></span>
</p>
<p>
  <span><a href="#h.1pxezwc">Collecting
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.1pxezwc">5</a></span>
</p>
<p>
  <span><a href="#h.49x2ik5">Processing
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.49x2ik5">5</a></span>
</p>
<p>
  <span><a href="#h.2p2csry">Storing
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.2p2csry">6</a></span>
</p>
<p>
  <span><a href="#h.147n2zr">Serving
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.147n2zr">6</a></span>
</p>
<p>
  <span><a href="#h.3o7alnk">System
      Configuration</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.3o7alnk">7</a></span>
</p>
<p>
  <span><a href="#h.eysnx4dpwebu">Minimum
      configuration</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.eysnx4dpwebu">7</a></span>
</p>
<p>
  <span><a href="#h.2grqrue">System
      configuration</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.2grqrue">7</a></span>
</p>
<p>
  <span><a href="#h.er8kqxpzkk9c">Network
      configuration</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.er8kqxpzkk9c">7</a></span>
</p>
<p>
  <span><a href="#h.jnu6liqyuy6w">Prerequisite for the minimum
      configuration</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.jnu6liqyuy6w">8</a></span>
</p>
<p>
  <span><a href="#h.m0k2jr9xgyc5">Data
      Source</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.m0k2jr9xgyc5">8</a></span>
</p>
<p>
  <span><a href="#h.v6ctr9tipvnl">Defense Center and Serving
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.v6ctr9tipvnl">8</a></span>
</p>
<p>
  <span><a href="#h.3fwokq0">Settings</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.3fwokq0">9</a></span>
</p>
<p>
  <span><a href="#h.3fwokq0">Basic
      configuration</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.3fwokq0">9</a></span>
</p>
<p>
  <span><a href="#h.x6622txijq3y">System
      configuration</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.x6622txijq3y">10</a></span>
</p>
<p>
  <span><a href="#h.20stsxpug9pj">Network
      configuration</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.20stsxpug9pj">10</a></span>
</p>
<p>
  <span><a href="#h.19c6y18">Settings</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.19c6y18">11</a></span>
</p>
<p>
  <span><a href="#h.19c6y18">Version Control of Source
      Code</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.19c6y18">11</a></span>
</p>
<p>
  <span><a href="#h.3tbugp1">Mata Elang LTS (Long Term Support) Version
      1.0</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.3tbugp1">11</a></span>
</p>
<p>
  <span><a href="#h.28h4qwu">Data Source</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.28h4qwu">12</a></span>
</p>
<p>
  <span><a href="#h.nmf14n">Defence
      Center</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.nmf14n">12</a></span>
</p>
<p>
  <span><a href="#h.37m2jsg">Collecting
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.37m2jsg">12</a></span>
</p>
<p>
  <span><a href="#h.1mrcu09">Processing
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.1mrcu09">12</a></span>
</p>
<p>
  <span><a href="#h.46r0co2">Storing
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.46r0co2">12</a></span>
</p>
<p>
  <span><a href="#h.2lwamvv">Serving
      Data</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.2lwamvv">13</a></span>
</p>
<p>
  <span><a href="#h.111kx3o">License</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.111kx3o">13</a></span>
</p>
<p>
  <span><a href="#h.3l18frh">Standard
      Coding</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.3l18frh">13</a></span>
</p>
<p>
  <span><a href="#h.206ipza">Development and Test
      Environment</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.206ipza">14</a></span>
</p>
<p>
  <span><a href="#h.4k668n3">Key areas to set up in Test
      Environment</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.4k668n3">14</a></span>
</p>
<p>
  <span><a href="#h.2zbgiuw">Process of Sensor Test Environment
      setup</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.2zbgiuw">14</a></span>
</p>
<p>
  <span><a href="#h.1egqt2p">Process of Data Processing Test Environment
      setup</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.1egqt2p">14</a></span>
</p>
<p>
  <span><a href="#h.3ygebqi">Process of Data Serving Test Environment
      setup</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.3ygebqi">15</a></span>
</p>
<p>
  <span><a href="#h.2dlolyb">Test Environment
      Management</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.2dlolyb">15</a></span>
</p>
<p>
  <span><a href="#h.sqyw64">Test Environment
      Checklist</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.sqyw64">16</a></span>
</p>
<p>
  <span><a href="#h.cbz6grohk6un">Contact for
      Inquiry</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.cbz6grohk6un">19</a></span>
</p>
<p>
  <span><a href="#h.1rvwp1q">Revision
      History</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.1rvwp1q">19</a></span>
</p>
<p>
  <span><a href="#h.wbqatkmb2nij">Appendix A: Installation
      manual</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.wbqatkmb2nij">20</a></span>
</p>
<p>
  <span><a href="#h.bcdkvvyvpnx0">Install Data Source ( Sensor
      )</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.bcdkvvyvpnx0">20</a></span>
</p>
<p>
  <span><a href="#h.mjkhxabu0fom">Install
      Mosquitto</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.mjkhxabu0fom">21</a></span>
</p>
<p>
  <span><a href="#h.hn38e7k723ho">Install Apache
      Cassandra</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.hn38e7k723ho">21</a></span>
</p>
<p>
  <span><a href="#h.yb3ld04l31kw">Install
      MongoDB</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.yb3ld04l31kw">24</a></span>
</p>
<p>
  <span><a href="#h.lk8brjnfjaqq">Install Apache Hadoop ( Single Node Cluster Installation
      )</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.lk8brjnfjaqq">25</a></span>
</p>
<p>
  <span><a href="#h.mq35fraz365v">Install
      Confluent</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.mq35fraz365v">29</a></span>
</p>
<p>
  <span><a href="#h.q3tzra4v0b1a">Install Apache
      Spark</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.q3tzra4v0b1a">30</a></span>
</p>
<p>
  <span><a href="#h.5yv1azihd0dc">Install
      Dashboard</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.5yv1azihd0dc">33</a></span>
</p>
<p>
  <span><a href="#h.p282qwd2zpnb">Install Stevia
      Visualization</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.p282qwd2zpnb">34</a></span>
</p>
<p>
  <span><a href="#h.2r0uhxc">Appendix B: Low Bandwidth Installation
      Manual</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.2r0uhxc">34</a></span>
</p>
<p>
  <span><a href="#h.1664s55">Appendix C:
      Troubleshooting</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.1664s55">34</a></span>
</p>
<p>
  <span><a href="#h.idp2g5u449zu">Appendix D: Use Case for Sensor
      Installation</a></span><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span><a
      href="#h.idp2g5u449zu">35</a></span>
</p>
<p><span></span></p>
<hr style="page-break-before: always; display: none" />
<p><span></span></p>
<ol start="1">
  <li>
    <h1 id="h.4i7ojhp" style="display: inline">
      <span>Overview of Mata Elang</span>
    </h1>
  </li>
</ol>
<ol start="1">
  <li>
    <h2 id="h.2xcytpi" style="display: inline">
      <span>Mata Elang</span>
    </h2>
  </li>
</ol>
<p>
  <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Many applications are
    beginning to face the challenges of big data, not to mention apps for
    analyzing network traffic [1].
  </span>
</p>
<p>
  <span>Network Intrusion Detection System (NIDS) is an application that is
    time-sensitive and requires a solution to the big data. Big data
    challenges are usually using the concept of 4V (Volume, Velocity
    Variety, Value). However, in some cases, especially NIDS, it requires a
    deeper understanding of the idea to define it because the
    characteristics of NIDS data do not always meet the concept.[1].
  </span>
</p>
<p>
  <span>Snort is a signature-based NIDS application that is commonly used. The
    architecture and mechanism cannot be said to be able to face the
    challenges of big data efficiently.
  </span>
</p>
<p>
  <span>Mata Elang as one of the case studies implementing Snort NIDS as IDS
    uses the following architecture,
  </span>
</p>
<p>
  <span>&#9679; In existing architecture, sensor placement must be on the same
    physical network with a defense center so that the deployment cost can
    be enormous.
  </span>
</p>
<p>
  <span>&#9679; Data alert storage is still using a centralized database
    technology, where if the data stored is getting bigger in volume,
    scaling will be severe.
  </span>
</p>
<p>
  <span>&#9679; Analytic and data aggregation is also carried out using a
    centralized system, so if the data grows more prominent, scaling will be
    critical. Of course, this implementation is not ready when &nbsp;facing
    the challenges of big data.
  </span>
</p>
<p>
  <span>Therefore, research is needed to prepare Snort NIDS to face the big
    data challenges.</span>
</p>
<p><span></span></p>
<ol start="2">
  <li>
    <h2 id="h.1ci93xb" style="display: inline">
      <span>Mata Elang Community</span>
    </h2>
  </li>
</ol>
<p>
  <span>For ecosystems to work appropriately, communities of participants need
    to exist. These participants should be able to develop products and
    services based on platform resources (via APIs). Experts in the panel
    observed some critical considerations in developing an ecosystem
    community, which include the need, 1) to establish a fair and
    transparent intellectual property model whereby third party developers
    can fairly monetize their developments, 2) to open up the platform to a
    sufficient degree to allow and encourage innovation, 3) to &#39;create
    community&#39; in the sense of enabling the exchange of ideas and
    fostering collaboration, and, 4) to provide an open door for feedback
    from the community about the position and direction of the ecosystem in
    the market.</span>
</p>
<p>
  <span>By enabling people to invest and create new products and services on
    the platform, the ecosystem can provide a more productive set of options
    to end-users. Moreover, the faster an ecosystem develops a positive
    reputation among developers and thus more join the platform, the more
    difficult and tedious it becomes for others to replicate such a deed.
    This reflects market expectations driving network effects. As more
    developers are attracted to the ecosystem, more users are drawn to new
    products and better services offered.</span>
</p>
<ol start="2">
  <li>
    <h1 id="h.3whwml4" style="display: inline">
      <span>System Architecture</span>
    </h1>
  </li>
</ol>
<p>
  <span>We will develop a defense center system architecture for a cloud
    environment. The system block diagram for this concept, as shown in
    Figure 1:</span>
</p>
<p id="h.2et92p0">
  <span>Figure 1. Cloud environment system concept for Snort-cloud-based IDS
    framework</span><span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 497.5px;
          height: 234.93px;
        "><img alt="" src="../assets/images/image9.png" style="
            width: 497.5px;
            height: 288.23px;
            margin-left: -0px;
            margin-top: -5.92px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<p>
  <span>The sensors or base modules are designed to run in the cloud computing
    environment and can be installed in the different networks from the core
    module (central defense system), as we can see in the system diagram.
    Defense centers will process and analyze reports generated by sensors.
    Figure 2 shows the recommended system architecture for the complete
    system, including the defense center, data source, and data
    serving.</span>
</p>
<p><span></span></p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 564.68px;
          height: 213.5px;
        "><img alt="" src="../assets/images/image2.png" style="
            width: 564.68px;
            height: 213.5px;
            margin-left: -0px;
            margin-top: -0px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<p>
  <span>Figure 2. System Architecture Diagram</span>
</p>
<ol start="3">
  <li>
    <h2 id="h.2bn6wsx" style="display: inline">
      <span>Data Source</span>
    </h2>
  </li>
</ol>
<p>
  <span>The first component of the data source is the IDS sensor. In this
    version of Mata Elang, the sensor use Snort&trade; as the core IDS
    engine. Soon we plan to use various &nbsp; &nbsp;IDS engines e.g
    Suricata, Wazuh, etc. &nbsp;The output of the sensors sent to the
    defense center via some types of transmission protocol, which could
    transport data at the lowest latency as possible. A fast and efficient
    transmission protocol is also mandatory for carrying sensor
    outputs.</span>
</p>
<ol start="4">
  <li>
    <h2 id="h.qsh70q" style="display: inline">
      <span>Defense Center</span>
    </h2>
  </li>
</ol>
<p>
  <span>The Defense Center is the part of the Mata Elang, the processing of
    which is maximized is the processing of data, from collecting data to
    storing data in a database. The central defense system is divided into
    three parts, namely collecting data, processing data, and storing
    data.</span>
</p>
<ol start="1">
  <li>
    <h3 id="h.1pxezwc" style="display: inline">
      <span>Collecting Data</span>
    </h3>
  </li>
</ol>
<p>
  <span>The data collection process is a continuation stage after the sensor
    receives data attacks that occur on a network. In conducting data
    collection, the system uses Apache Kafka. Kafka here is a bridge between
    the sensor and spark as the primary data processors. In the process of
    Kafka, the data will be received and processed by the MQTT server. In
    MQTT the data will be processed by coding and simplification using Kafka
    Avro. Then it will be connected to the confluent so that the data is
    ready to proceed to spark via Apache Kafka.</span>
</p>
<ol start="2">
  <li>
    <h3 id="h.49x2ik5" style="display: inline">
      <span>Processing Data</span>
    </h3>
  </li>
</ol>
<p>
  <span>Data processing in the Mata Elang system uses Apache Spark. The Apache
    Spark feature used in data processing is a streaming feature that can
    record and process data in live time. In streaming processing, a Spark
    will stream brokers to Kafka. The streaming process includes the
    following steps:</span>
</p>
<ul>
  <li>
    <span>It deserializes AVRO data with an existing registry scheme.</span>
  </li>
  <li>
    <span>It converts data into data frames for Apache Spark&#39;s data
      abstraction using the map function.</span>
  </li>
  <li>
    <span>It executes the existing data frame aggregation process using the
      subtraction function.</span>
  </li>
  <li>
    <span>It writes to Apache Cassandra.</span>
  </li>
</ul>
<ol start="1">
  <li>
    <h3 id="h.2p2csry" style="display: inline">
      <span>Storing Data</span>
    </h3>
  </li>
</ol>
<p id="h.147n2zr">
  <span>The first part of the defense center receiving data streams from remote
    sensors and then split these data into two types of flow process: stream
    job and batch job. The stream job process serves real-time monitoring
    information, while the batch job process is used for analytical data.
  </span>
</p>
<ol start="2">
  <li>
    <h3 style="display: inline">
      <span>Serving Data</span>
    </h3>
  </li>
</ol>
<p>
  <span>There are two components in the serving data module: dashboards and the
    map.</span>
</p>
<ol start="1">
  <li><span>Dashboard</span></li>
</ol>
<p>
  <span>For the dashboards, we refer to the popular standard metrics for
    network security applications by the SANS Institute. It consists of
    :</span>
</p>
<ul>
  <li>
    <span>Event Monitoring. It based on the result of streaming jobs</span>
  </li>
  <li>
    <span>Event Statistics. It based on the result of streaming jobs</span>
  </li>
  <li>
    <span>Top Signatures. It based on the result of batch jobs (the total
      number of &nbsp;event grouped by the signature&#39;s name)</span>
  </li>
  <li>
    <span>Top Protocol. It based on the result of batch jobs (the total number
      of &nbsp;event grouped by the protocol)</span>
  </li>
  <li>
    <span>Sensor Statistics. It based on the result of batch jobs (the total
      number of the event for each sensor)</span>
  </li>
  <li>
    <span>Daily-monthly-annual report</span>
  </li>
  <li>
    <span>User-role-profile-menu-management </span>
  </li>
</ul>
<ol start="2">
  <li><span>Maps</span></li>
</ol>
<p>
  <span>A cyber threat map, also known as a cyber attack map, is a real-time
    map of the computer security attacks that are going on at any given
    time. Beams of light, represented by different colors showing where an
    attack comes from and where it is going</span>
</p>
<ol start="3">
  <li>
    <h1 style="display: inline">
      <span>System Configuration</span>
    </h1>
  </li>
</ol>
<ol start="1">
  <li>
    <h2 id="h.eysnx4dpwebu" style="display: inline">
      <span>Minimum configuration</span>
    </h2>
  </li>
</ol>
<p>
  <span>The minimum configuration is a configuration with one sensor and one
    host of defense center.
  </span>
</p>
<ol start="3">
  <li>
    <h3 id="h.2grqrue" style="display: inline">
      <span>System configuration</span>
    </h3>
  </li>
</ol>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 565px;
          height: 213.99px;
        "><img alt="" src="../assets/images/image13.png" style="
            width: 565px;
            height: 213.99px;
            margin-left: -0px;
            margin-top: -0px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<p>
  <span>Figure 3. System Architecture Diagram</span>
</p>
<p>
  <span>Figure 3 shows the minimum configuration for Mata Elang with one sensor
    and one monitored network.</span>
</p>
<ol start="4">
  <li>
    <h3 id="h.er8kqxpzkk9c" style="display: inline">
      <span>Network configuration</span>
    </h3>
  </li>
</ol>
<p>
  <span>Figure 4. Network Topology</span><span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 565px;
          height: 237.06px;
        "><img alt="" src="../assets/images/image4.png" style="
            width: 565px;
            height: 237.06px;
            margin-left: -0px;
            margin-top: -0px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<p>
  <span>Figure 4 shows the common topology with two switches and one PC for the
    defense center. At a minimum use of the configuration, we only use one
    sensor to monitor the private network. In this case, the sensor is
    placed in a different network address with the defense center.</span>
</p>
<p><span></span></p>
<ol start="5">
  <li>
    <h3 id="h.jnu6liqyuy6w" style="display: inline">
      <span>Prerequisite for the minimum configuration</span>
    </h3>
  </li>
</ol>
<ol start="1">
  <li>
    <h4 id="h.m0k2jr9xgyc5" style="display: inline">
      <span>Data Source</span>
    </h4>
  </li>
</ol>
<a id="t.a085fa87302ec5320f7ffbfc2f8fb315cb1a3cb6"></a><a id="t.0"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Requirements</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>Version/Model</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>Quantity</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>Notes</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Hardware</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>CPU</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>Intel Core 2 Duo or more</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>LAN card interfaces</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1-gigabit ether or more</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>2</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>RAM</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>2GB or more</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Hardisk</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>100GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Operating System</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Linux Ubuntu Server </span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>18.04</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Software</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Git</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>2.7</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Docker</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>19.03</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
  </tbody>
</table>
<p>
  <span>Minimum bandwidth: 10Mbps for installation</span>
</p>
<p><span></span></p>
<ol start="2">
  <li>
    <h4 id="h.v6ctr9tipvnl" style="display: inline">
      <span>Defense Center and Serving Data</span>
    </h4>
  </li>
</ol>
<a id="t.942d6f64203b2860e5b606d4797b0e5b7eb8eac1"></a><a id="t.1"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Requirements</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>&nbsp;Version/Model</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>Quantity</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>Notes</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Hardware</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>CPU </span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>Intel Core i7 / Ryzen 7 or more</span>
        </p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>LAN card interfaces</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>&nbsp;1-gigabit ether or more</span>
        </p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>2</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>RAM</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>32GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Hardisk</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>500GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Operating System</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Linux Ubuntu Server</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>18.04</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Software</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>OpenJDK/Oracle Java</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>8</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Scala</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>2.11</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>SBT</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1.3</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Git</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>2.7</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Apache Cassandra</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>3.11</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Apache Hadoop</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>3.2</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>MongoDB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>4.2</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Docker</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>19.03</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>NodeJS</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>12.14 (LTS)</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Python</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>3.5</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
  </tbody>
</table>
<p>
  <span>Minimum bandwidth: 10Mbps for installation</span>
</p>
<ol start="2">
  <li>
    <h2 id="h.3fwokq0" style="display: inline">
      <span>Common configuration</span>
    </h2>
  </li>
</ol>
<p id="h.x6622txijq3y">
  <span>Figure 5. System Architecture Diagram</span><span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 564.68px;
          height: 213.5px;
        "><img alt="" src="../assets/images/image2.png" style="
            width: 564.68px;
            height: 213.5px;
            margin-left: -0px;
            margin-top: -0px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<p id="h.20stsxpug9pj">
  <span>Figure 5 shows the basic system configuration where the Mata Elang can
    monitor more than one network.
  </span>
</p>
<h1 id="h.hm99vhplhrkk">
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 602px;
          height: 293.33px;
        "><img alt="" src="../assets/images/image3.png" style="
            width: 602px;
            height: 293.33px;
            margin-left: -0px;
            margin-top: -0px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</h1>
<p><span>Figure 6. Network Topology</span></p>
<p>
  <span>Figure 6 shows the physical network configuration of the Mata Elang for
    multi-sensors &nbsp; containing: &nbsp;two tappers, two sensors, two
    switches, and one defense center</span>
</p>
<ol start="4">
  <li>
    <h1 id="h.19c6y18" style="display: inline">
      <span>Version Control of Source Code </span>
    </h1>
  </li>
</ol>
<p>
  <span>We use &nbsp; GitHub as out application version control. Mata Elang
    Project is hosted on Github as a public organization for collaboration.
    (</span><span><a
      href="https://www.google.com/url?q=https://github.com/mata-elang-pens&amp;sa=D&amp;source=editors&amp;ust=1613153648879000&amp;usg=AOvVaw1rkd9zaYjbieaVk1ZgPiLn">https://github.com/mata-elang-pens</a></span><span>)</span>
</p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 549.5px;
          height: 345.95px;
        "><img alt="" src="../assets/images/image10.png" style="
            width: 549.5px;
            height: 345.95px;
            margin-left: -0px;
            margin-top: -0px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<p id="h.tyjcwt">
  <span>Figure 7. Mata Elang Repositories</span>
</p>
<p>
  <span>The repository of Mata Elang is publicly accessible. Everyone can
    propose changes by forking the repository by using the pull request
    feature. Some sections in Mata Elang Architecture requires additional
    authorization by Mata Elang Founders to change as described in the </span><span>Strategic Document
    section 5.</span>
</p>
<ol start="3">
  <li>
    <h2 id="h.3tbugp1" style="display: inline">
      <span>Mata Elang LTS (Long Term Support) Version 1.0</span>
    </h2>
  </li>
</ol>
<p>
  <span>At present, Mata Elang is in version 1.0. It means we do not rule out
    the possibility that Mata Elang will make updates in various aspects.
    So, we will do Long Term Support with the conditions below:</span>
</p>
<ol start="6">
  <li>
    <h3 id="h.28h4qwu" style="display: inline">
      <span>Data Source</span>
    </h3>
  </li>
</ol>
<p>
  <span>For the Long Term Support version, we do support according to the
    available versions of each requirement. Here is the Long Term Support
    Version for Data Source:</span>
</p>
<ul>
  <li>
    <span>Linux Ubuntu Server version 18.04 </span>
  </li>
  <li>
    <span>Python version 3.8.2 </span>
  </li>
  <li>
    <span>Java version 8 </span>
  </li>
  <li>
    <span>Python-PIP version 3.8.2 </span>
  </li>
  <li>
    <span>Docker version 3 </span>
  </li>
  <li>
    <span>Snort version 2.9.15.1 </span>
  </li>
</ul>
<ol start="1">
  <li>
    <h3 id="h.nmf14n" style="display: inline">
      <span>Defense Center</span>
    </h3>
  </li>
</ol>
<ol start="1">
  <li>
    <h4 id="h.37m2jsg" style="display: inline">
      <span>Collecting Data</span>
    </h4>
  </li>
</ol>
<p>
  <span>For the Long Term Support version, we do support according to the
    available versions of each requirement. Here is the Long Term Support
    Version for Collecting Data:</span>
</p>
<ul>
  <li>
    <span>Linux Ubuntu Server version 18.04 </span>
  </li>
  <li>
    <span>Kafka version included in confluent</span>
  </li>
  <li>
    <span>Zookeeper version included in confluent</span>
  </li>
  <li>
    <span>Mosquitto version 1.6.9</span>
  </li>
  <li>
    <span>Confluent version 5.4.0</span>
  </li>
</ul>
<ol start="1">
  <li>
    <h4 id="h.1mrcu09" style="display: inline">
      <span>Processing Data</span>
    </h4>
  </li>
</ol>
<p>
  <span>For the Long Term Support version, we do support according to the
    available versions of each requirement. Here is the Long Term Support
    Version for Processing Data:</span>
</p>
<ul>
  <li>
    <span>Linux Ubuntu Server version 18.04</span>
  </li>
  <li>
    <span>Java version 8</span>
  </li>
  <li>
    <span>Scala version 2.11</span>
  </li>
  <li>
    <span>Apache Spark version 2.3.4</span>
  </li>
  <li>
    <span>Apache Hadoop version 2.10.0</span>
  </li>
</ul>
<ol start="1">
  <li>
    <h4 id="h.46r0co2" style="display: inline">
      <span>Storing Data</span>
    </h4>
  </li>
</ol>
<p>
  <span>For the Long Term Support version, we do support according to the
    available versions of each requirement. Here is the Long Term Support
    Version for Storing Data:</span>
</p>
<ul>
  <li>
    <span>Linux Ubuntu Server version 18.04</span>
  </li>
  <li>
    <span>MongoDB version 4.2.3</span>
  </li>
</ul>
<ul>
  <li>
    <span>Java version 8</span>
  </li>
</ul>
<ul>
  <li>
    <span>Apache Hadoop version 2.10.0</span>
  </li>
  <li>
    <span>Apache Cassandra version 3.11.6</span>
  </li>
</ul>
<ol start="1">
  <li>
    <h4 id="h.2lwamvv" style="display: inline">
      <span>Serving Data</span>
    </h4>
  </li>
</ol>
<p>
  <span>For the Long Term Support version, we do support according to the
    available versions of each requirement. Here is the Long Term Support
    Version for Serving Data:</span>
</p>
<ul>
  <li>
    <span>Python version 3</span>
  </li>
  <li>
    <span>NodeJs version 12.16.1 LTS</span>
  </li>
</ul>
<ol start="1">
  <li>
    <h2 id="h.111kx3o" style="display: inline">
      <span>License</span>
    </h2>
  </li>
</ol>
<p>
  <span>We considered using GNU GPLv2. By using this license, we may charge a
    fee for the physical act of transferring a copy and there is a
    possibility to offer professional support and warranty protection in
    exchange for a fee.</span>
</p>
<ol start="5">
  <li>
    <h1 id="h.3l18frh" style="display: inline">
      <span>Standard Coding</span>
    </h1>
  </li>
</ol>
<p>
  <span>The Mata Elang source code consists of several programming and
    scripting languages. The scripting language is used for automating build
    and docker containers for sensors.</span>
</p>
<p>
  <span>For this reason, we standardized coding scheme for extensible
    development reasons:</span>
</p>
<ul>
  <li>
    <span>No more than a single statement per line, for bash scripting, there
      might be a pipelining (||) or chaining (&amp;&amp;), so it is
      separated by a backslash and the new line between statements.</span><span style="
            overflow: hidden;
            display: inline-block;
            margin: 0px 0px;
            border: 0px solid #000000;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
            width: 602px;
            height: 68.5px;
          "><img alt="" src="../assets/images/image1.png" style="
              width: 602px;
              height: 68.5px;
              margin-left: 0px;
              margin-top: 0px;
              transform: rotate(0rad) translateZ(0px);
              -webkit-transform: rotate(0rad) translateZ(0px);
            " title="" /></span>
  </li>
  <li>
    <span>Comments must be added for understandable reasons in every statement
      context.</span>
  </li>
  <li>
    <span>Use of the information before including the coding script</span>
  </li>
  <li>
    <span>Naming variables are adjusted globally for easy understand by others
    </span>
  </li>
  <li>
    <span>Error handling will be explained in the troubleshooting section in
      Appendix C</span>
  </li>
</ul>
<p><span></span></p>
<ol start="6">
  <li>
    <h1 id="h.206ipza" style="display: inline">
      <span>Development and Test Environment</span>
    </h1>
  </li>
</ol>
<ol start="1">
  <li>
    <h2 id="h.4k668n3" style="display: inline">
      <span>&nbsp;Key areas to set up in Test Environment</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>System and applications</span>
  </li>
  <li><span>Test Data</span></li>
  <li>
    <span>Database server</span>
  </li>
  <li>
    <span>Front-end running environment</span>
  </li>
  <li>
    <span>Client operating system</span>
  </li>
  <li><span>Browser</span></li>
  <li>
    <span>Hardware includes server operating system</span>
  </li>
  <li><span>Network</span></li>
  <li>
    <span>Document required for testing like reference documents/configuration
      guides/installation guides/user manuals</span>
  </li>
</ol>
<ol start="1">
  <li>
    <h2 id="h.2zbgiuw" style="display: inline">
      <span>Process of Sensor Test Environment setup</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Setup of Test Server</span>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Install GNU Linux Operating System</span>
  </li>
  <li>
    <span>Install Python3, Python3-PIP, and Docker packages</span>
  </li>
  <li>
    <span>Install Mata Elang Sensors</span>
  </li>
</ol>
<ol start="2">
  <li>
    <span>Setup of Network</span>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Internet Setup</span>
  </li>
  <li>
    <span>LAN/WIFI Setup</span>
  </li>
  <li>
    <span>Private Network Setup</span>
  </li>
</ol>
<ol start="3">
  <li>
    <span>Test of Server Setup</span>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Check Python3, Python3-PIP, and Docker installation.</span>
  </li>
  <li>
    <span>Check whether the Mata Elang sensor service is working properly</span>
  </li>
  <li>
    <span>Checking the connection between Mata Elang sensor and Mata Elang
      Cloud System established</span>
  </li>
  <li>
    <span>I was checking whether the server can send data to MQTT Broker.</span>
  </li>
</ol>
<ol start="4">
  <li>
    <span>Bug Reporting</span>
  </li>
</ol>
<ol start="1">
  <li>
    <h2 id="h.1egqt2p" style="display: inline">
      <span>Process of Data Processing Test Environment setup</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Setup of Test Server</span>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Install GNU Linux Operating System</span>
  </li>
  <li>
    <span>Install Java 8 (JDK and JRE)</span>
  </li>
  <li>
    <span>Install Scala</span>
  </li>
  <li>
    <span>Install SBT</span>
  </li>
  <li>
    <span>Install Apache Hadoop</span>
  </li>
  <li>
    <span>Install Apache Spark</span>
  </li>
</ol>
<ol start="2">
  <li>
    <span>Setup of Network</span>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Internet Setup</span>
  </li>
  <li>
    <span>LAN/WIFI Setup</span>
  </li>
  <li>
    <span>Private Network Setup</span>
  </li>
</ol>
<ol start="3">
  <li>
    <span>Test of Server Setup</span>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Checking whether the Big Data platform is working properly</span>
  </li>
</ol>
<ol start="4">
  <li>
    <span>Bug Reporting</span>
  </li>
  <li>
    <span>Creating/Collecting Test Data for the Test Environment</span>
  </li>
</ol>
<ol start="1">
  <li>
    <h2 id="h.3ygebqi" style="display: inline">
      <span>Process of Data Serving Test Environment setup</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Setup of Test Server</span>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Install GNU Linux Operating System</span>
  </li>
  <li>
    <span>Install NodeJS and NPM packages</span>
  </li>
  <li>
    <span>Install NodeJS dependencies using `npm install`</span>
  </li>
</ol>
<ol start="2">
  <li>
    <span>Setup of Network</span>
  </li>
  <li>
    <span>Test of Server Setup</span>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Checking whether rest API application can make a connection to
      database server</span>
  </li>
  <li>
    <span>Checking whether rest API is accessible by other client using Server
      IP</span>
  </li>
</ol>
<ol start="4">
  <li>
    <span>Bug Reporting</span>
  </li>
</ol>
<ol start="1">
  <li>
    <h2 id="h.2dlolyb" style="display: inline">
      <span>Test Environment Management</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Maintenance of the server with all the updated versions of test
      environments.</span>
  </li>
  <li>
    <span>Monitoring of the environment.</span>
  </li>
  <li>
    <span>Updating/deleting outdated test-environments.</span>
  </li>
  <li>
    <span>Investigation of issues on the environment.</span>
  </li>
</ol>
<ol start="1">
  <li>
    <h2 id="h.sqyw64" style="display: inline">
      <span>Test Environment Checklist</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Sensor Environment</span>
  </li>
</ol>
<a id="t.a26eef6660bce47caad3e2a3bfde9ed5a168a002"></a><a id="t.2"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="2">
        <p><span>Requirements</span></p>
      </td>
      <td colspan="2" rowspan="1">
        <p><span>Status</span></p>
      </td>
      <td colspan="1" rowspan="2">
        <p><span>Command Check</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Yes</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>No</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Hardware</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>CPU Intel Core 2 Duo</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>lshw -short | grep processor</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>LAN card interfaces</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>lshw -short | grep network</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>RAM 2GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>lshw -short | grep memory</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Hardisk 100GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>lshw -short | grep disk</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Software</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Linux Ubuntu server 18.04</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>cat /etc/os-release</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Git</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>git --version</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Docker</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>docker -v</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="2">
  <li id="h.gjdgxs">
    <span>Data Processing Environment</span>
  </li>
</ol>
<a id="t.c6a194b53da119c71a6a3af8d04977d91f327b93"></a><a id="t.3"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="2">
        <p><span>Requirements</span></p>
      </td>
      <td colspan="2" rowspan="1">
        <p><span>Status</span></p>
      </td>
      <td colspan="1" rowspan="2">
        <p><span>Command Check</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Yes</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>No</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Hardware</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>CPU Intel Core i7 / Ryzen 7</span>
        </p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>lshw -short | grep processor</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>LAN card interfaces</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>lshw -short | grep network</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>RAM 16 GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>lshw -short | grep memory</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Hardisk 500GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>lshw -short | grep disk</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Software</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Linux ubuntu server 18.04</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>cat /etc/os-release</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Java 8</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>java -version</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Scala</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>scala -version</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>SBT</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>sbt --version</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Git</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>git --version</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="3">
  <li>
    <span>Data Storing Environment</span>
  </li>
</ol>
<a id="t.29f4a780bcc30544e8fae0ca7b6904a6fb3c6524"></a><a id="t.4"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="2">
        <p><span>Requirements</span></p>
      </td>
      <td colspan="2" rowspan="1">
        <p><span>Status</span></p>
      </td>
      <td colspan="1" rowspan="2">
        <p><span>Command Check</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Yes</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>No</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Hardware</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>CPU Intel Core i3</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>lshw -short | grep processor</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>LAN card interfaces</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>lshw -short | grep network</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>RAM 4GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>lshw -short | grep memory</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Hardisk 500 GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>lshw -short | grep disk</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Software</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Linux ubuntu server 18.04</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>cat /etc/os-release</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Mongodb</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>mongod --version</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Apache Cassandra</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>cqlsh</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Apache Hadoop</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>hadoop version</span></p>
      </td>
    </tr>
  </tbody>
</table>
<hr style="page-break-before: always; display: none" />
<p><span></span></p>
<ol start="4">
  <li>
    <span>Data Serving Environment</span>
  </li>
</ol>
<a id="t.a1d4d8d5f398e08aa0f1ac395e675a0a0f05429f"></a><a id="t.5"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="2">
        <p><span>Requirements</span></p>
      </td>
      <td colspan="2" rowspan="1">
        <p><span>Status</span></p>
      </td>
      <td colspan="1" rowspan="2">
        <p><span>Command Check</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Yes</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>No</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Hardware</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>CPU Intel Core 2 Duo</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>lshw -short | grep processor</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>LAN card interfaces</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>lshw -short | grep network</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>RAM 4GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>lshw -short | grep memory</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Hardisk 500 GB</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>lshw -short | grep disk</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="4" rowspan="1">
        <p><span>Software</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Linux ubuntu server 18.04</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>cat /etc/os-release</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Node JS</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>node -v</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Git</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>git --version</span></p>
      </td>
    </tr>
  </tbody>
</table>
<hr style="page-break-before: always; display: none" />
<p><span></span></p>
<ol start="7">
  <li>
    <h1 id="h.cbz6grohk6un" style="display: inline">
      <span>Contact for Inquiry</span>
    </h1>
  </li>
</ol>
<p>
  <span>Mata Elang Lead Developer Team, Mr. Ferry Astika Saputra, Department of
    Informatics and Computer Engineering, Politeknik Elektronika Negeri
    Surabaya (PENS), Email: ferryas@pens.ac.id, Phone +62-82139214988.</span>
</p>
<ol start="8">
  <li>
    <h1 id="h.1rvwp1q" style="display: inline">
      <span>Revision History</span>
    </h1>
  </li>
</ol>
<a id="t.8e679358ef4ebd5949a74311f8937244db3dd179"></a><a id="t.6"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>Version</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>Date</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>PIC</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>ToC</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>Revised content</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>1</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>14 Dec 2019</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>PTI</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>2</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>20 Dec 2019</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>PTI</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>3</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>26 Dec 2019</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>PTI</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>4</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>31 Dec 2019</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>PTI</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>5</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>10 Jan 2020</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>PTI</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>-</span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>6</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>21 Feb 2020</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span>3,4</span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p>
          <span>Added system configuration and long term support versions</span>
        </p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
      <td colspan="1" rowspan="1">
        <p><span></span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<hr style="page-break-before: always; display: none" />
<h1 id="h.4bvk7pj"><span></span></h1>
<h1 id="h.wbqatkmb2nij">
  <span>Appendix A: Installation manual</span>
</h1>
<ol start="1">
  <li>
    <h2 id="h.bcdkvvyvpnx0" style="display: inline">
      <span>Install Data Source ( Sensor )</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Installing Docker </span><span><a
        href="https://www.google.com/url?q=https://docs.docker.com/install/&amp;sa=D&amp;source=editors&amp;ust=1613153648966000&amp;usg=AOvVaw3XIQB6SFWp1xCRMMtH5v1e">https://docs.docker.com/install/</a></span>
  </li>
  <li>
    <span>Enable Docker Service</span>
  </li>
</ol>
<a id="t.9c8ed8a4ef187c6b8dc86cc3e6dfde74275a3e12"></a><a id="t.7"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl enable docker</span>
        </p>
        <p>
          <span>$ sudo systemctl start docker</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<ol start="3">
  <li>
    <span>Server preparation, configure the network interface to in promiscuous
      mode. Install </span><span>ifupdown</span><span>&nbsp;package. Then, edit
    </span><span>/etc/network/interfaces</span><span>&nbsp;file, add some line like the
      down below:</span>
  </li>
</ol>
<a id="t.cb364138a8368af4c6ad164ae33b3b464ad1235f"></a><a id="t.8"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>auto eth1</span></p>
        <p>
          <span>iface eth1 inet manual</span>
        </p>
        <p>
          <span>&nbsp; &nbsp;up ip address add 0/0 dev eth1</span>
        </p>
        <p>
          <span>&nbsp; &nbsp;up ip link set eth1 up</span>
        </p>
        <p>
          <span>&nbsp; &nbsp;up ip link set eth1 promisc on</span>
        </p>
        <p>
          <span>&nbsp; &nbsp;down ip link set eth1 promisc off</span>
        </p>
        <p>
          <span>&nbsp; &nbsp;down ip link set eth1 down</span>
        </p>
        <p><span></span></p>
        <p><span>auto eth2</span></p>
        <p><span>iface eth2 inet dhcp</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p><span>Note: </span></p>
<ul>
  <li>
    <span>Don&#39;t forget to change the </span><span>eth1</span><span>&nbsp;and
    </span><span>eth2</span><span>&nbsp;with your server network interface name</span>
  </li>
  <li>
    <span>eth1</span><span>&nbsp;must be connected to the tapper port where the port is set for
      mirroring destination port</span>
  </li>
</ul>
<ol start="4">
  <li>
    <span>Restart network service or restart your server</span>
  </li>
</ol>
<a id="t.83cdf9bfee19a8dd392e2e85587be77a8176908a"></a><a id="t.9"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl restart networking</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<ol start="5">
  <li>
    <span>Download Sensor Installer from </span><span><a
        href="https://www.google.com/url?q=https://github.com/mata-elang-pens/sensor-installer&amp;sa=D&amp;source=editors&amp;ust=1613153648973000&amp;usg=AOvVaw0wqsyXPbbQjjwQf4J2BjPc">mata-elang-pens/sensor-installer</a></span><span>&nbsp;GitHub
      repository
      (https://github.com/mata-elang-pens/sensor-installer)</span>
  </li>
  <li>
    <span>Add executable permission to setup.sh</span>
  </li>
</ol>
<a id="t.1d6665f5364be4aa42ed9e8767c456fee5e49ee6"></a><a id="t.10"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo chmod +x setup.sh</span>
        </p>
        <p>
          <span>$ sudo chmod +x update-rule.sh</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<ol start="7">
  <li>
    <span>Run the setup.sh script with the following command and wait until the
      setup finished</span>
  </li>
</ol>
<a id="t.79627e8901a77e039199bb0736bc4e13daf1dd86"></a><a id="t.11"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ sudo ./setup.sh</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="8">
  <li>
    <span>To Update Snort Rules use this command :</span>
  </li>
</ol>
<a id="t.01f5169cc2246c5c18dffe862c2f4f4e7eebd90e"></a><a id="t.12"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo ./update-rule.sh</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="2">
  <li>
    <h2 id="h.mjkhxabu0fom" style="display: inline">
      <span>Install Mosquitto</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Update APT index and install the new Ubuntu Package Update</span>
  </li>
</ol>
<a id="t.2a4b296e6cc1cad84b01527817878b9e7adf5876"></a><a id="t.13"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ sudo apt update</span></p>
        <p><span>$ sudo apt upgrade</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="2">
  <li>
    <span>Install mosquitto using APT</span>
  </li>
</ol>
<a id="t.1e86e72f9bfa612822e92668f3f7fd61b92ef22c"></a><a id="t.14"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo apt install mosquitto mosquitto-clients</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="3">
  <li>
    <span>Enable mosquitto service</span>
  </li>
</ol>
<a id="t.828b4fcc8fb8f4b12ffd2abc37d92cc74fab1c83"></a><a id="t.15"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl enable mosquitto.service</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="4">
  <li>
    <span>Start mosquitto service</span>
  </li>
</ol>
<a id="t.90e000d123d2c4d0d5d1198037f60f27212bfe07"></a><a id="t.16"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl start mosquitto.service</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<ol start="3">
  <li>
    <h2 id="h.hn38e7k723ho" style="display: inline">
      <span>Install Apache Cassandra</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Add Cassandra Debian Repository</span>
  </li>
</ol>
<a id="t.97874c941ca7103e48c305cc13997faeacc3718e"></a><a id="t.17"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ echo &ldquo;deb </span><span><a
              href="https://www.google.com/url?q=http://www.apache.org/dist/cassandra/debian&amp;sa=D&amp;source=editors&amp;ust=1613153648982000&amp;usg=AOvVaw1M4l4LghZFCPpJuslK7RFs">http://www.apache.org/dist/cassandra/debian</a></span><span>&nbsp;36x
            main&rdquo; | sudo tee -a
            /etc/apt/sources.list.d/cassandra.list</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="2">
  <li>
    <span>Import the Cassandra Repository key</span>
  </li>
</ol>
<a id="t.a91b0d77c856c4805af1354393f3028158e91704"></a><a id="t.18"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ curl https://downloads.apache.org/cassandra/KEYS | sudo
            apt-key add -</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="3">
  <li>
    <span>Update the APT index</span>
  </li>
</ol>
<a id="t.27a01b1471baa6c6ec87035c7b45bb3f629f3a40"></a><a id="t.19"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ sudo apt update</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="4">
  <li>
    <span>If there&#39;s an error &quot;GPG error: </span><span><a
        href="https://www.google.com/url?q=http://www.apache.org/&amp;sa=D&amp;source=editors&amp;ust=1613153648985000&amp;usg=AOvVaw1f-hV-I3UxW9JwEZ38hsxL">http://www.apache.org</a></span><span>&nbsp;36x
      InRelease: The following signatures couldn&#39;t be
      verified because the public key is not available: NO_PUBKEY
      A278B781FE4B2BDA&quot;</span>
  </li>
</ol>
<a id="t.74a54caacb0e7d529647398fedb304aeb395d32f"></a><a id="t.20"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo apt-key adv --keyserver pool.sks-keyservers.net
            --recv-key A278B781FE4B2BDA</span>
        </p>
        <p><span>$ sudo apt update</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="5">
  <li>
    <span>Install Cassandra using APT</span>
  </li>
</ol>
<a id="t.98940778446017f551d5d6913f80d62480ea17f5"></a><a id="t.21"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo apt install cassandra</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="6">
  <li>
    <span>Enable Cassandra Service</span>
  </li>
</ol>
<a id="t.9a12bc9250dec59b85a033dad8752bf82e497f7c"></a><a id="t.22"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl enable cassandra.service</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="7">
  <li>
    <span>Start Cassandra Service</span>
  </li>
</ol>
<a id="t.eed98ba425de82651cadea44a04c8a108d6fdeaf"></a><a id="t.23"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl start cassandra.service</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="8">
  <li>
    <span>Configuring Apache Cassandra, edit /etc/cassandra/cassandra.yaml
      file, change the authenticator, rpc_address, and broadcast_rpc_address
      like the following value below:</span>
  </li>
</ol>
<a id="t.eaa396b1ec15232ec9d43431f351454b136ff2d7"></a><a id="t.24"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>authenticator: PasswordAuthenticator</span>
        </p>
        <p><span>...</span></p>
        <p><span>rpc_address: 0.0.0.0</span></p>
        <p><span>...</span></p>
        <p>
          <span>broadcast_rpc_address: localhost</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="9">
  <li>
    <span>Restart Cassandra Service</span>
  </li>
</ol>
<a id="t.02738487425410abf2a48b5830f2af6bafd142c6"></a><a id="t.25"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl restart cassandra.service</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="10">
  <li>
    <span>Login to cassandra with default user</span>
  </li>
</ol>
<a id="t.08cbde6a5dbcc3b2cffa4de35a0c5e31e7c07ff8"></a><a id="t.26"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ cqlsh -u cassandra -p cassandra</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>NB : When there is an error </span><span>&quot;</span><span>Connection error: (&#39;Unable to connect to any
    servers&#39;,
    {&#39;127.0.0.1&#39;: TypeError (&#39;ref () does not take keyword
    arguments&#39;,)})</span><span>&quot;</span><span>. Run the command below to
    resolve this problem. After that, run the
    cqlsh command again.</span>
</p>
<a id="t.c045d49340ae4326abd034843dc5a3e68f1059a7"></a><a id="t.27"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo apt install python-pip</span>
        </p>
        <p>
          <span>$ pip install cassandra-driver</span>
        </p>
        <p>
          <span>$ export CQLSH_NO_BUNDLED=true</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="11">
  <li>
    <span>Create a new Apache Cassandra user with the following command:</span>
  </li>
</ol>
<a id="t.4987e3b09e68906c8be6cdfbe80d7f049ac63234"></a><a id="t.28"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>&gt; CREATE USER </span><span>yourusername</span><span>&nbsp;WITH PASSWORD
            &#39;</span><span>yourpassword</span><span>&#39; SUPERUSER;</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="12">
  <li>
    <span>Import Apache Cassandra keyspace, copy file cassandraQueryScript.cql
      to defense center server</span>
  </li>
  <li>
    <span>Import the database keyspace with the following command:</span>
  </li>
</ol>
<a id="t.73b0449d3b07ce154a0ae1ff03f57eca78acf15e"></a><a id="t.29"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ cqlsh -u </span><span>yourusername</span><span>&nbsp;-f
            cassandraQueryScript.cql</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="14">
  <li>
    <span>Login using admin</span>
  </li>
</ol>
<a id="t.53fafaadab71837ae861ef68e2857e8beba8beb4"></a><a id="t.30"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ cqlsh -u </span><span>yourusername</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="15">
  <li>
    <span>Use kaspa keyspace</span>
  </li>
</ol>
<a id="t.e36951728af1adc343c6ef951eb5f5e194c336e2"></a><a id="t.31"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>&gt; use kaspa;</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="16">
  <li>
    <span>Run this SQL script to create a new user. Change the red-colored text
      to match your configuration.</span>
  </li>
</ol>
<a id="t.5c0b420127ad2cf68a561c628f4e16b369081492"></a><a id="t.32"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>&gt; INSERT INTO kaspa.user (username, company, email,
            first_name, group, last_name, password_hash, time_joined) VALUES
            (</span><span>&lsquo;</span><span>yourusername</span><span>&rsquo;</span><span>,
          </span><span>&lsquo;</span><span>yourcompany</span><span>&rsquo;</span><span>,
            &lsquo;</span><span>youremail@example.com</span><span>&rsquo;,
            &lsquo;</span><span>yourfirstname</span><span>&rsquo;, &lsquo;</span><span>yourgroup</span><span>&rsquo;,
            &lsquo;</span><span>yourlastname</span><span>&rsquo;,
            &lsquo;$6$rounds=656000$aS2RFKm/fkVcHWi1$QaltqzL92qlShWP9hG2vWIHZ1qCzRnIXApavcCBvaewGQGZArBNvQRazfMabJonZaXzmwMwuodGFYAV3h5Pzw0&rsquo;,
            toTimeStamp(now()));</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<ol start="4">
  <li>
    <h2 id="h.yb3ld04l31kw" style="display: inline">
      <span>Install MongoDB</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Import MongoDB Repository Key</span>
  </li>
</ol>
<a id="t.c89bd7196c3cf4de9b7c4fa31805106729ca487c"></a><a id="t.33"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc
            | sudo apt-key add -</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="2">
  <li>
    <span>Add MongoDB Ubuntu Repository</span>
  </li>
</ol>
<a id="t.b29cd20895c0742d254c01d8cdb4f4052af43fb7"></a><a id="t.34"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ echo </span><span>&ldquo;</span><span>deb
            https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2
            multiverse&rdquo; | sudo tee -a
            /etc/apt/sources.list.d/mongodb-org-4.2.list</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="3">
  <li>
    <span>Update APT index</span>
  </li>
</ol>
<a id="t.27a01b1471baa6c6ec87035c7b45bb3f629f3a40"></a><a id="t.35"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ sudo apt update</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="4">
  <li>
    <span>Install MongoDB</span>
  </li>
</ol>
<a id="t.f004acaa45dce378a1820654230391eb10df05ab"></a><a id="t.36"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo apt install mongodb-org</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="5">
  <li>
    <span>Edit /etc/mongod.conf to configure IP binding and replica set in
      order to enable access to the database from outside network and enable
      change stream which is essential for real-time application (such as
      STEVIA).
    </span>
  </li>
</ol>
<a id="t.0f44676394ebdb69a76495ce6e0dc5f090a17e20"></a><a id="t.37"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>net:</span></p>
        <p><span>&nbsp; port: 27017</span></p>
        <p>
          <span>&nbsp; bindIp: 0.0.0.0</span>
        </p>
        <p><span>... </span></p>
        <p><span>replication:</span></p>
        <p>
          <span>&nbsp; replSetName: rs0</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="6">
  <li>
    <span>Enable Mongo Service</span>
  </li>
</ol>
<a id="t.95231a1a260a1e919e60f82972dee7dcec80ab7e"></a><a id="t.38"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl enable mongod.service</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="7">
  <li>
    <span>Start Mongo Service</span>
  </li>
</ol>
<a id="t.738cc97ec5ee889ebc64d6b19514bb0f4c9561c9"></a><a id="t.39"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl start mongod.service</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="8">
  <li>
    <span>Create an admin user for MongoDB and initiate the replica set using
      the following command inside mongo-shell:</span>
  </li>
</ol>
<a id="t.22c93f43765d76a2ea55c779f438d404ecbd5b1b"></a><a id="t.40"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ mongo</span></p>
        <p><span>&gt; use admin</span></p>
        <p>
          <span>&gt; db.createUser({user: &ldquo;</span><span>yourusername</span><span>&rdquo;, pwd:
            &ldquo;</span><span>yourpassword</span><span>&rdquo;, roles: [&ldquo;root&rdquo;]})</span>
        </p>
        <p><span>&gt; db.getUsers()</span></p>
        <p><span>&gt; rs.initiate()</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="9">
  <li>
    <span>Edit /etc/mongod.conf file again to enable the authentication, change
      the following section like below:</span>
  </li>
</ol>
<a id="t.0a1fc313f3ae4a4b9959b787577b14d301923e5f"></a><a id="t.41"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>...</span></p>
        <p><span>security:</span></p>
        <p>
          <span>&nbsp; authorization: &#39;enabled&#39;</span>
        </p>
        <p><span>...</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p>
  <span>Note: admin user must be created while the authorization is
    disabled</span>
</p>
<ol start="10">
  <li>
    <span>Restart Mongo Service</span>
  </li>
</ol>
<a id="t.c36e7a11d00467b1bcfa2d04470852884dbf8805"></a><a id="t.42"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl restart mongod.service</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<ol start="5">
  <li>
    <h2 id="h.lk8brjnfjaqq" style="display: inline">
      <span>Install Apache Hadoop ( Single Node Cluster Installation )</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>The required additional step before the Hadoop installation :</span>
  </li>
</ol>
<ul>
  <li>
    <span>Java installation (minimum version 8) OpenJDK/Oracle</span>
  </li>
  <li>
    <span>Set the JAVA_HOME environment variable</span>
  </li>
</ul>
<ol start="2">
  <li>
    <span>Download Hadoop</span>
  </li>
</ol>
<a id="t.42f71b1594c0f12361d9cf3de303579158773204"></a><a id="t.43"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ wget
            https://www-eu.apache.org/dist/hadoop/common/hadoop-3.2.1/hadoop-3.2.1.tar.gz</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="3">
  <li>
    <span>Extract the Hadoop archive</span>
  </li>
</ol>
<a id="t.95226bd56f811bfa69caae3840c2f63441a892b5"></a><a id="t.44"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ tar -xzf hadoop-3.2.1.tar.gz</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="4">
  <li>
    <span>Rename the hadoop directory name</span>
  </li>
</ol>
<a id="t.2927859000e6a93994989a3d17a172d1330002b2"></a><a id="t.45"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ mv hadoop-3.2.1 hadoop</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="5">
  <li>
    <span>(optional) Remove the downloaded archive to save space</span>
  </li>
</ol>
<a id="t.9f30cd0f882d204ae496528391317d8e4ac5ec38"></a><a id="t.46"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ rm -f hadoop-3.2.1.tar.gz</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="6">
  <li>
    <span>Add Hadoop to user PATH, edit /home/yourusername/.bashrc with any
      text editor (ex: </span><span>nano .bashrc</span><span>), add this line at
      the bottom:</span>
  </li>
</ol>
<a id="t.87044316a2411a9c5ee61bd4433e6453c6291c48"></a><a id="t.47"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>HADOOP_HOME=/home/</span><span>yourusername</span><span>/hadoop</span>
        </p>
        <p>
          <span>PATH=$PATH:$HADOOP_HOME/bin:$HADOOP_HOME/sbin</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="7">
  <li>
    <span>Load the new environment:</span>
  </li>
</ol>
<a id="t.f03851de4c65360d8d407e3f444bd38edd5ca412"></a><a id="t.48"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ source ~/.bashrc</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="8">
  <li>
    <span>Check the Hadoop version using these command:</span>
  </li>
</ol>
<a id="t.2391c4f009614f3da30ddfe38314e38ecd796213"></a><a id="t.49"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ hadoop version</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="9">
  <li>
    <span>Make sure you can connect using ssh to the localhost without a
      password. If ssh still asks the password run these command and then
      check again:</span>
  </li>
</ol>
<a id="t.25c15cd0a639e96fd7630ecb739f30d925666584"></a><a id="t.50"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ ssh-keygen -t rsa -P &#39;&#39; -f ~/.ssh/id_rsa</span>
        </p>
        <p>
          <span>$ cat ~/.ssh/id_rsa.pub &gt;&gt; ~/.ssh/authorized_keys</span>
        </p>
        <p>
          <span>$ chmod 0600 ~/.ssh/authorized_keys</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="10">
  <li>
    <span>Configure the Hadoop, edit the
      /home/yourusername/hadoop/etc/hadoop/core-site.xml file, add the
      following content with this between configuration tag:</span>
  </li>
</ol>
<a id="t.f4a35debd61f49f77d72bfead2bfce6e199aba5d"></a><a id="t.51"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>&lt;configuration&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;fs.defaultFS&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;value&gt;hdfs://localhost:9000&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&lt;/configuration&gt;</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>Note: if you already have portainer or other app installed on port 9000
    change the hadoop port to other than 9000 or change the portainer port.
    Don&#39;t forget to change the KaspaCoreSystem application.conf
    too</span>
</p>
<ol start="11">
  <li>
    <span>Edit the /home/yourusername/hadoop/etc/hadoop/hdfs-site.xml file, add
      the following content with this between configuration tag:</span>
  </li>
</ol>
<a id="t.6089feb33b2303209255cc42961f4924e8cf44d2"></a><a id="t.52"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>&lt;configuration&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;dfs.namenode.name.dir&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;value&gt;/home/hduser/hadoop/dfs/name&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;dfs.datanode.data.dir&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;value&gt;/home/hduser/hadoop/dfs/data&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;dfs.replication&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp; &lt;value&gt;1&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;dfs.namenode.rpc-bind-host&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;value&gt;0.0.0.0&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&lt;/configuration&gt;</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="12">
  <li>
    <span>Edit the /home/yourusername/hadoop/etc/hadoop/mapred-site.xml file,
      add the following content with this between configuration tag:</span>
  </li>
</ol>
<a id="t.769023fdfbd1d15db588b102e3b68a161e4be7ce"></a><a id="t.53"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>&lt;configuration&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;mapreduce.framework.name&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;value&gt;yarn&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            &lt;name&gt;yarn.resourcemanager.address&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            &lt;value&gt;localhost:8032&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;mapreduce.application.classpath&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;value&gt;$HADOOP_MAPRED_HOME/share/hadoop/mapreduce/*:$HADOOP_MAPRED_HOME/share/hadoop/mapreduce/lib/*&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&lt;/configuration&gt;</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="13">
  <li>
    <span>Edit the /home/yourusername/hadoop/etc/hadoop/yarn-site.xml file, add
      the following content with this between configuration tag:</span>
  </li>
</ol>
<a id="t.af2b0672f2db6d0673ff846daef1d075109a1385"></a><a id="t.54"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>&lt;configuration&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;yarn.nodemanager.aux-services&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;value&gt;mapreduce_shuffle&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;property&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;name&gt;yarn.nodemanager.env-whitelist&lt;/name&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &nbsp; &nbsp;
            &lt;value&gt;JAVA_HOME,HADOOP_COMMON_HOME,HADOOP_HDFS_HOME,HADOOP_CONF_DIR,CLASSPATH_PREPEND_DISTCACHE,HADOOP_YARN_HOME,HADOOP_MAPRED_HOME&lt;/value&gt;</span>
        </p>
        <p>
          <span>&nbsp; &nbsp; &lt;/property&gt;</span>
        </p>
        <p>
          <span>&lt;/configuration&gt;</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="14">
  <li>
    <span>Format Hadoop DFS</span>
  </li>
</ol>
<a id="t.889f15f5149b2cca2471720d8b513c9baa4b276c"></a><a id="t.55"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ hdfs namenode -format</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="15">
  <li>
    <span>Start the Hadoop Namenode and Yarn</span>
  </li>
</ol>
<a id="t.8b43a39cc4a3a4e11cd25786f57ddd9cbc7be955"></a><a id="t.56"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span># To start:</span></p>
        <p>
          <span>$ start-dfs.sh &amp;&amp; start-yarn.sh</span>
        </p>
        <p><span></span></p>
        <p><span># To stop it, run : </span></p>
        <p>
          <span>$ stop-yarn.sh &amp;&amp; stop-dfs.sh</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="16">
  <li>
    <span>Create required directory</span>
  </li>
</ol>
<a id="t.372769791aae0015cca649e344677621ece07f6c"></a><a id="t.57"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ hdfs dfs -mkdir -p hdfs://localhost:9000/user/</span><span>yourusername</span><span>/job</span>
        </p>
        <p>
          <span>$ hdfs dfs -mkdir -p hdfs://localhost:9000/user/</span><span>yourusername</span><span>/kaspa</span>
        </p>
        <p>
          <span>$ hdfs dfs -mkdir -p
            hdfs://localhost:9000/user/</span><span>yourusername</span><span>/kafka-checkpoint</span>
        </p>
        <p>
          <span>$ hdfs dfs -mkdir -p
            hdfs://localhost:9000/user/</span><span>yourusername</span><span>/kaspa-checkpoint</span>
        </p>
        <p>
          <span>$ hdfs dfs -mkdir -p
            hdfs://localhost:9000/user/</span><span>yourusername</span><span>/schema/raw_kaspa</span>
        </p>
        <p>
          <span>$ hdfs dfs -mkdir -p
            hdfs://localhost:9000/user/</span><span>yourusername</span><span>/file/maxmind</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="6">
  <li>
    <h2 id="h.mq35fraz365v" style="display: inline">
      <span>Install Confluent</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Make sure you already installed Docker at the Defense Center
      environment, see </span><span><a
        href="https://www.google.com/url?q=https://docs.docker.com/install/&amp;sa=D&amp;source=editors&amp;ust=1613153649029000&amp;usg=AOvVaw2XGWi1DhceTCfPCJbPFq-r">https://docs.docker.com/install/</a></span><span>&nbsp;for
      Docker installation tutorial.</span>
  </li>
  <li>
    <span>Edit </span><span>docker-compose.yml</span><span>&nbsp;file,
      find the line contain this :</span>
  </li>
</ol>
<a id="t.e66b41a0f966a224116e85b88192a81f4e87e831"></a><a id="t.58"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>KAFKA_ADVERTISED_LISTENERS:
            PLAINTEXT://broker:29092,PLAINTEXT_HOST://</span><span>yourip</span><span>:9092</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p>
  <span>Change </span><span>&lt;your-ip&gt;</span><span>&nbsp;with
    your host IP</span>
</p>
<ol start="3">
  <li>
    <span>Pull the image</span>
  </li>
</ol>
<a id="t.d92c9e097893d564a5ba4da5ac040c77e402f756"></a><a id="t.59"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose pull</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="4">
  <li>
    <span>Start Docker services in daemon mode using these command:</span>
  </li>
</ol>
<a id="t.b684b98763d4126da96477a2c316213ad2b702a9"></a><a id="t.60"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose up -d</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="5">
  <li>
    <span>Make sure that all service running</span>
  </li>
</ol>
<a id="t.d457008d93f1bb3f5ebb62a6a423bacc177548cf"></a><a id="t.61"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ docker-compose ps</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="6">
  <li>
    <span>Check if Kafka connector already deployed using these command make
      sure the output is [&quot;mqtt-source&quot;] :</span>
  </li>
</ol>
<a id="t.0b69a593e47a2abf6df829ed27401b15654b2219"></a><a id="t.62"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ curl http://localhost:8083/connectors</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="7">
  <li>
    <span>If it is not, restart the connect-add service using these command and
      then try checking again:</span>
  </li>
</ol>
<a id="t.9e02fef9731e46842c6d78ab5075095f617b7d3f"></a><a id="t.63"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose start connect-add</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<ol start="7">
  <li>
    <h2 id="h.q3tzra4v0b1a" style="display: inline">
      <span>Install Apache Spark</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Make sure you already installed Docker at Defense Center environment,
      see </span><span><a
        href="https://www.google.com/url?q=https://docs.docker.com/install/&amp;sa=D&amp;source=editors&amp;ust=1613153649036000&amp;usg=AOvVaw0sq-1eOQnQWM8vnRmJPAnm">https://docs.docker.com/install/</a></span><span>&nbsp;for
      Docker installation tutorial.</span>
  </li>
</ol>
<p><span></span></p>
<ol start="2">
  <li>
    <span>Edit docker-compose.yml file, change &lt;your-ip&gt; with your host
      IP, and then save it.</span>
  </li>
</ol>
<p><span></span></p>
<ol start="3">
  <li><span>Pull the image</span></li>
</ol>
<a id="t.d92c9e097893d564a5ba4da5ac040c77e402f756"></a><a id="t.64"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose pull</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="4">
  <li>
    <span>Clone the KaspaCoreSystem repository, then navigate the terminal to
      that directory.</span>
  </li>
</ol>
<a id="t.c2c9ae64d6e14742b1d0211f640bffdc41f3d415"></a><a id="t.65"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ git clone
            https://github.com/mata-elang-pens/KaspaCoreSystem.git
            &amp;&amp; cd KaspaCoreSystem</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="5">
  <li>
    <span>Change the value in src/main/resources/application.conf to match your
      environment.</span>
  </li>
</ol>
<p><span></span></p>
<ol start="6">
  <li>
    <span>Also change the MongoDB IP from 127.0.0.1 to your IP in
      src/main/scala/me/mamotis/kaspacore/jobs/DataStream.scala</span>
  </li>
</ol>
<p><span></span></p>
<ol start="7">
  <li>
    <span>Run these command from KaspaCoreSystem directory:</span>
  </li>
</ol>
<a id="t.e74b7903a95c930869160f8df637cffb28bac49b"></a><a id="t.66"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ sbt assembly</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="8">
  <li>
    <span>Copy target/scala-2.11/KaspaCore-assembly-0.1.jar file to defense
      center and place to this directory with docker-compose.yml and other
      files.</span>
  </li>
</ol>
<p><span></span></p>
<ol start="9">
  <li>
    <span>Start Docker services in daemon mode using these command:</span>
  </li>
</ol>
<a id="t.b684b98763d4126da96477a2c316213ad2b702a9"></a><a id="t.67"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose up -d</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="10">
  <li>
    <span>Make sure that all service running</span>
  </li>
</ol>
<a id="t.d457008d93f1bb3f5ebb62a6a423bacc177548cf"></a><a id="t.68"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ docker-compose ps</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="11">
  <li>
    <span>Open the web browser, and navigate to http://your-server-ip:8080,
      check if there is still running app, if not, try restarting the
      spark-submit service and then check again :</span>
  </li>
</ol>
<a id="t.452b308fb3c2478f2f7988ed465f9187f6f002d0"></a><a id="t.69"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose start spark-submit</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="12">
  <li>
    <span>Next, we need to set up the scheduled batch job. First, create a
      directory to place the required files for the batch job.</span>
  </li>
</ol>
<a id="t.2c01f3b29585ac99f31ded87b73eb767e36accff"></a><a id="t.70"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo mkdir -p /etc/mataelang-spark</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="13">
  <li>
    <span>Create a new file called spark.env</span>
  </li>
</ol>
<a id="t.942e8354e5f22e9dffaacba1c1c04f17ae708dc2"></a><a id="t.71"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo nano /etc/mataelang-spark/spark.env</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p>
  <span><br /></span><span>add the following lines to the spark.env file (just
    change the
    SPARK_MASTER_HOST with your server IP)</span>
</p>
<a id="t.e8d88cf31b81aca2cfb197799a96439cfd38b496"></a><a id="t.72"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>SPARK_MASTER_HOST: </span><span>yourip</span>
        </p>
        <p>
          <span>SPARK_MASTER_PORT: 7077</span>
        </p>
        <p>
          <span>SPARK_TOTAL_EXECUTOR_CORES: 1</span>
        </p>
        <p>
          <span>SPARK_CONF_FILE_PATH: /opt/spark.conf</span>
        </p>
        <p>
          <span>SPARK_SUBMIT_JAR: file:///opt/KaspaCore-assembly-0.1.jar</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p>
  <span><br />Next, create a new file called spark.conf</span>
</p>
<a id="t.d512a4349768c06770a0d42b354f4e570590c9e9"></a><a id="t.73"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo nano /etc/mataelang-spark/spark.conf</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p>
  <span><br /></span><span>and then add the following lines to the spark.conf file</span>
</p>
<a id="t.e3d58b88740e694b26ea48a21b1613a5cff34261"></a><a id="t.74"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>spark.submit.deployMode=client</span>
        </p>
        <p>
          <span>spark.executor.cores=1</span>
        </p>
        <p>
          <span>spark.executor.memory=2g</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="14">
  <li>
    <span>Copy application file (KaspaCore-assembly-0.1.jar) to the
      /etc/mataelang-spark/</span>
  </li>
</ol>
<a id="t.04722e9a9cb05e60417fe90f76882a5a7ee52251"></a><a id="t.75"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo cp </span><span>/path/to/</span><span>KaspaCore-assembly-0.1.jar /etc/mataelang-spark/</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="15">
  <li>
    <span>Add cronjob for the KaspaCoreSystem batch job. Run the following
      command to open the crontab file:</span>
  </li>
</ol>
<a id="t.694d244da86efd81f5775d9d6e9903ebf2c8e5f7"></a><a id="t.76"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ sudo crontab -e</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>After the text editor opened, add the following line :</span>
</p>
<a id="t.392ca285f4b923c8d3256c21b8396c01982e7516"></a><a id="t.77"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>0 0 * * * docker run --rm --name spark-submit-daily --network
            host -v /etc/localtime:/etc/localtime -v
            /etc/timezone:/etc/timezone -v
            /etc/mataelang-spark/spark.conf:/opt/spark.conf -v
            /etc/mataelang-spark/KaspaCore-assembly-0.1.jar:/opt/KaspaCore-assembly-0.1.jar
            --env-file /etc/mataelang-spark/spark.env -e
            SPARK_SUBMIT_CLASS=me.mamotis.kaspacore.jobs.DailyCount
            mfscy/me-spark-submit:latest</span>
        </p>
        <p>
          <span>0 0 1 * * docker run --rm --name spark-submit-monthly --network
            host -v /etc/localtime:/etc/localtime -v
            /etc/timezone:/etc/timezone -v
            /etc/mataelang-spark/spark.conf:/opt/spark.conf -v
            /etc/mataelang-spark/KaspaCore-assembly-0.1.jar:/opt/KaspaCore-assembly-0.1.jar
            --env-file /etc/mataelang-spark/spark.env -e
            SPARK_SUBMIT_CLASS=me.mamotis.kaspacore.jobs.MonthlyCount
            mfscy/me-spark-submit:latest</span>
        </p>
        <p>
          <span>0 0 1 1 * docker run --rm --name spark-submit-yearly --network
            host -v /etc/localtime:/etc/localtime -v
            /etc/timezone:/etc/timezone -v
            /etc/mataelang-spark/spark.conf:/opt/spark.conf -v
            /etc/mataelang-spark/KaspaCore-assembly-0.1.jar:/opt/KaspaCore-assembly-0.1.jar
            --env-file /etc/mataelang-spark/spark.env -e
            SPARK_SUBMIT_CLASS=me.mamotis.kaspacore.jobs.AnnuallyCount
            mfscy/me-spark-submit:latest</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="8">
  <li>
    <h2 id="h.5yv1azihd0dc" style="display: inline">
      <span>Install Dashboard</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>Make sure you already installed Docker at Defense Center environment,
      see </span><span><a
        href="https://www.google.com/url?q=https://docs.docker.com/install/&amp;sa=D&amp;source=editors&amp;ust=1613153649049000&amp;usg=AOvVaw3igU842nU3p4CzAjHvRxMu">https://docs.docker.com/install/</a></span><span>&nbsp;for
      Docker installation tutorial.</span>
  </li>
  <li>
    <span>Don&#39;t forget to fill the two files kaspaclient.env and
      kaspaservice.env</span>
  </li>
</ol>
<p>
  <span>List form in the kaspaclient.env file :</span>
</p>
<a id="t.9fd0e50ba6773ecf28e8a093673aa05a8e14149c"></a><a id="t.78"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>API_HOST=</span></p>
        <p><span>API_USER=</span></p>
        <p><span>API_PASS=</span></p>
        <p><span>SECRET_TOKEN=</span></p>
        <p><span>SECRET_PASSWORD=</span></p>
        <p><span>SECRET_KEY=</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>List form in the kaspaservice.env file</span>
</p>
<a id="t.0417ca3f8969cc9bb5f48feb8e1a3ea6e685b341"></a><a id="t.79"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>CASSANDRA_USERNAME=</span></p>
        <p><span>CASSANDRA_PASSWORD=</span></p>
        <p>
          <span>CASSANDRA_CLUSTER_HOST=</span>
        </p>
        <p><span>DEFAULT_OINKCODE=</span></p>
        <p><span>SECRET_KEY=</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="3">
  <li>
    <span>Pull the image</span>
  </li>
</ol>
<a id="t.d92c9e097893d564a5ba4da5ac040c77e402f756"></a><a id="t.80"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose pull</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="4">
  <li>
    <span>Start Docker services in daemon mode using these command:</span>
  </li>
</ol>
<a id="t.b684b98763d4126da96477a2c316213ad2b702a9"></a><a id="t.81"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose up -d</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="5">
  <li>
    <span>Make sure that all service running</span>
  </li>
</ol>
<a id="t.d457008d93f1bb3f5ebb62a6a423bacc177548cf"></a><a id="t.82"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ docker-compose ps</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="6">
  <li>
    <span>Open a web browser, and navigate to http://your-server-ip:8800</span>
  </li>
</ol>
<ol start="9">
  <li>
    <h2 id="h.p282qwd2zpnb" style="display: inline">
      <span>Install Stevia Visualization</span>
    </h2>
  </li>
</ol>
<ol start="1">
  <li>
    <span>The stevia repository clone from GitHub uses the following
      syntax:</span>
  </li>
</ol>
<a id="t.6aa02100788410c4e988844ac6b134fe63e18cdc"></a><a id="t.83"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ git clone https://github.com/azlkiniue/stevia.git</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="2">
  <li>
    <span>After the cloning process is complete, then enter into the stevia
      folder, and then edit the configuration file using the following
      syntax:</span>
  </li>
</ol>
<a id="t.e23d9ad8c24d9c5f590cdd5a5e706a89cb66a365"></a><a id="t.84"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ nano stevia/resources/values.js</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>then adjust the IP address and the main location with the display to be
    visualized.</span>
</p>
<ol start="3">
  <li>
    <span>Next, to install stevia, we use the npm command, which is:</span>
  </li>
</ol>
<a id="t.a5b59222a2b42c2af339c447800bc76d7f7fe7da"></a><a id="t.85"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ npm install</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>To run stevia in the background, use the following syntax:</span>
</p>
<a id="t.9cace1c1cf4180cb99afa7bea7a2da9c04535eb4"></a><a id="t.86"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ nohup npm start &amp;</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>Or, you can use other tools, such as </span><span><a
      href="https://www.google.com/url?q=https://www.npmjs.com/package/forever&amp;sa=D&amp;source=editors&amp;ust=1613153649056000&amp;usg=AOvVaw0qQ5qcis_BW1wiJCrp2pcf">forever</a></span><span>&nbsp;and
  </span><span><a
      href="https://www.google.com/url?q=https://www.npmjs.com/package/nodemon&amp;sa=D&amp;source=editors&amp;ust=1613153649057000&amp;usg=AOvVaw06DRD9FzEbEEwEaIVpmjGN">nodemon</a></span><span>.</span>
</p>
<p>
  <span>The application will be available at port 1228.</span>
</p>
<h1 id="h.2r0uhxc">
  <span>Appendix B: Low Bandwidth Installation Manual</span>
</h1>
<p>
  <span>In installing Low Bandwidth, a new registration docker will be
    provided. so that it will be lighter to install on low bandwidth
    internet. for the installation steps will follow the installation manual
    that has been provided above.</span>
</p>
<h1 id="h.1664s55">
  <span>Appendix C: Troubleshooting</span>
</h1>
<ol start="1">
  <li>
    <span>When installing Apache Cassandra</span>
  </li>
</ol>
<ul>
  <li>
    <span>If there&#39;s an error &quot;GPG error: </span><span><a
        href="https://www.google.com/url?q=http://www.apache.org/&amp;sa=D&amp;source=editors&amp;ust=1613153649058000&amp;usg=AOvVaw0611tOxlalxNgYdSttiTXe">http://www.apache.org</a></span><span>&nbsp;36x
      InRelease: The following signatures couldn&#39;t be
      verified because the public key is not available: NO_PUBKEY
      A278B781FE4B2BDA&quot;</span>
  </li>
</ul>
<a id="t.b31deb665ed0025e990ea5b6c31a7545951b7743"></a><a id="t.87"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo apt-key adv --keyserver pool.sks-keyservers.net
            --recv-key A278B781FE4B2BDA &amp;&amp; sudo apt update</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="2">
  <li>
    <span>When Installing Apache Hadoop</span>
  </li>
</ol>
<ul>
  <li>
    <span>If you have a Portainer installed on port 9000 change the Hadoop port
      to other than 9000 or change the Portainer port. Don&#39;t forget to
      change the KaspaCoreSystem application.conf too</span>
  </li>
  <li>
    <span>If you check the version of Hadoop, and there is an error $JAVA_HOME
      not found. Check whether java is installed or not. Make sure that the
      java in use is java version 8.</span>
  </li>
</ul>
<ol start="3">
  <li>
    <span>When installing the Defense Center</span>
  </li>
</ol>
<ul>
  <li>
    <span>If Kafka connector doesn&#39;t connect, please restart the </span><span>connect-add</span><span>&nbsp;service
      using these command and then try checking
      again:</span>
  </li>
</ul>
<a id="t.9e02fef9731e46842c6d78ab5075095f617b7d3f"></a><a id="t.88"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ docker-compose start connect-add</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="4">
  <li>
    <span>When there is an error &quot;</span><span>Connection error: (&#39;Unable to connect to any
      servers&#39;,
      {&#39;127.0.0.1&#39;: TypeError (&#39;ref () does not take keyword
      arguments&#39;,)})</span><span>&quot; please use the following syntax:</span>
  </li>
</ol>
<a id="t.c045d49340ae4326abd034843dc5a3e68f1059a7"></a><a id="t.89"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo apt install python-pip</span>
        </p>
        <p>
          <span>$ pip install cassandra-driver</span>
        </p>
        <p>
          <span>$ export CQLSH_NO_BUNDLED=true</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="5">
  <li>
    <span>When the Hadoop version didn&rsquo;t found after executing hadoop
      version command, run the following command :
    </span>
  </li>
</ol>
<a id="t.8c60e71c6ed7b563ab43bb197816a13c3646c2c1"></a><a id="t.90"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<ol start="6">
  <li>
    <span>When error happened while starting Hadoop dfs because JAVA_HOME not
      set or not found, edit the hadoop.env file in $HADOOP_HOME/etc/hadoop/
      directory. And set the JAVA_HOME with the installed java directory.
      Example :
    </span>
  </li>
</ol>
<a id="t.1a2a931e47f9048e8afd781db24ee7b2a8e6aabd"></a><a id="t.91"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<h1 id="h.idp2g5u449zu">
  <span>Appendix D: Use Case for Sensor Installation</span>
</h1>
<ol start="1">
  <li>
    <span>Copy the Mata Elang sensor installation file. </span>
  </li>
  <li>
    <span>Make sure we are in the sensor directory, then give permission to
      setup.sh and update rule.sh with the command as shown.</span>
  </li>
</ol>
<a id="t.1e12437b7845f747903d426e89b647e6353ef8d3"></a><a id="t.92"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo chmod +x setup.sh update-rule.sh</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p><span>Example : </span></p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 579px;
          height: 119px;
        "><img alt="" src="../assets/images/image11.png" style="
            width: 579px;
            height: 411.99px;
            margin-left: -0px;
            margin-top: -0px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ol start="3">
  <li>
    <span>Install setup.sh, using the sudo setup.sh command. When the command
      is run, several installation questions will be presented as shown
      below.</span>
  </li>
</ol>
<a id="t.79627e8901a77e039199bb0736bc4e13daf1dd86"></a><a id="t.93"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ sudo ./setup.sh</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Example :</span>
</p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 552.67px;
          height: 17px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 578.65px;
            height: 455.4px;
            margin-left: -0px;
            margin-top: -84.94px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<p>
  <span>some of these questions include :</span>
</p>
<ul>
  <li>
    <span>Protected Subnet, here we give an example with 192.168.1.0/24.</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 503px;
          height: 17px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 579px;
            height: 439.73px;
            margin-left: -0px;
            margin-top: -95.65px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>External Subnet, here we use the default setup, i.e. any.</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 504.33px;
          height: 22px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 579.38px;
            height: 444.98px;
            margin-left: -0px;
            margin-top: -110px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>MQTT topic (default snoqttv5)</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 503px;
          height: 21px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 579px;
            height: 444.92px;
            margin-left: -0px;
            margin-top: -124.97px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>Mosquitto (MQTT Broker), here we give an example IP 192.168.1.102
      (Mosquitto&#39;s IP in the defense center)</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 503px;
          height: 20px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 578.99px;
            height: 444.64px;
            margin-left: -0px;
            margin-top: -138.88px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>Mosquitto (MQTT Broker) PORT, the default PORT is 1883.</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 504.33px;
          height: 21px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 579.38px;
            height: 444.92px;
            margin-left: -0px;
            margin-top: -153.97px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>Device ID, device ID will be obtained when opening kaspa
      client.</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 501.67px;
          height: 20px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 578.99px;
            height: 444.84px;
            margin-left: -0px;
            margin-top: -170.93px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<p>
  <span>Note: To edit Device ID, do the following command</span>
</p>
<ol start="1">
  <li>
    <span>First, open the information contained in the sensor directory, by
      typing the following command.</span>
  </li>
</ol>
<a id="t.7ecb70b1c754ba60c046dc436556e29ba7b96278"></a><a id="t.94"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span>$ sudo -i</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 458.33px;
          height: 38px;
        "><img alt="" src="../assets/images/image12.png" style="
            width: 579.24px;
            height: 444.91px;
            margin-left: -0px;
            margin-top: -90.98px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ol start="2">
  <li>
    <span>Navigate the directory to the sensor with the command
    </span>
  </li>
</ol>
<a id="t.6ec2deca7d9d9a75780c70937e62352040f72140"></a><a id="t.95"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span># cd sensor</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 460.33px;
          height: 20px;
        "><img alt="" src="../assets/images/image12.png" style="
            width: 579.48px;
            height: 444.94px;
            margin-left: -0px;
            margin-top: -155.98px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ol start="3">
  <li>
    <span>Next, look at the contents of the sensor directory, including hidden
      files with the following command. Then there will be a .env file which
      will then be edited</span>
  </li>
</ol>
<a id="t.4dcb339c6ecc6687177a72d3f1b4cfabeb7d6770"></a><a id="t.96"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span># ll</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>when the command is run will display as shown</span>
</p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 474.6px;
          height: 184px;
        "><img alt="" src="../assets/images/image12.png" style="
            width: 579px;
            height: 444.99px;
            margin-left: -0px;
            margin-top: -260.99px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ol start="4">
  <li>
    <span>Then edit the .env file with the following command
    </span>
  </li>
</ol>
<a id="t.d4c2982ebdd4511f728c4e951bdc92f6028e02c3"></a><a id="t.97"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p><span># nano .env</span></p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 472.6px;
          height: 20px;
        "><img alt="" src="../assets/images/image14.png" style="
            width: 579px;
            height: 444.94px;
            margin-left: -0px;
            margin-top: -424.94px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ol start="5">
  <li>
    <span>Change the value from each parameter to match with your
      configuration</span>
  </li>
</ol>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 473.4px;
          height: 165px;
        "><img alt="" src="../assets/images/image5.png" style="
            width: 578.99px;
            height: 444.98px;
            margin-left: -0px;
            margin-top: -84px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>Enter the availability of network interfaces</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 564px;
          height: 31px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 579px;
            height: 444.83px;
            margin-left: -0px;
            margin-top: -188.92px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>Network Interfaces: according to the network interfaces used for
      sensors. For example, using a LAN or Wifi, so an active interface will
      appear.</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 563.67px;
          height: 20px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 579px;
            height: 444.84px;
            margin-left: -0px;
            margin-top: -216.92px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>Company (enter your company name)</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 565.67px;
          height: 20px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 579px;
            height: 444.84px;
            margin-left: -0px;
            margin-top: -229.91px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>Your choice (choose according to your needs. Community / Registered
      rules. Here we exemplify by choosing 2 (registered)</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 563.67px;
          height: 85px;
        "><img alt="" src="../assets/images/image6.png" style="
            width: 579px;
            height: 444.93px;
            margin-left: -0px;
            margin-top: -245.96px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ul>
  <li>
    <span>Enter the oinkcode you have.</span>
  </li>
</ul>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 563.67px;
          height: 346px;
        "><img alt="" src="../assets/images/image7.png" style="
            width: 579px;
            height: 444.99px;
            margin-left: -0px;
            margin-top: -98.99px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ol start="4">
  <li>
    <span>Turn on the Mata Elang sensor service with the command</span>
  </li>
</ol>
<a id="t.e0475c192ce537168ba39d779bd52ae8dafa91cb"></a><a id="t.98"></a>
<table>
  <tbody>
    <tr>
      <td colspan="1" rowspan="1">
        <p>
          <span>$ sudo systemctl start mataelang-snort</span>
        </p>
      </td>
    </tr>
  </tbody>
</table>
<p><span></span></p>
<p>
  <span>when the command is run will display as shown</span>
</p>
<p>
  <span style="
          overflow: hidden;
          display: inline-block;
          margin: 0px 0px;
          border: 0px solid #000000;
          transform: rotate(0rad) translateZ(0px);
          -webkit-transform: rotate(0rad) translateZ(0px);
          width: 579px;
          height: 49px;
        "><img alt="" src="../assets/images/image8.png" style="
            width: 579px;
            height: 444.97px;
            margin-left: -0px;
            margin-top: -395.97px;
            transform: rotate(0rad) translateZ(0px);
            -webkit-transform: rotate(0rad) translateZ(0px);
          " title="" /></span>
</p>
<ol start="5">
  <li>
    <span>Installation completed. Now, we can wait for the sensor to download
      the rule while the sensor starting up.</span>
  </li>
</ol>
<div>
  <p><span></span></p>
  <p><span></span></p>
</div>
</body>

</html>
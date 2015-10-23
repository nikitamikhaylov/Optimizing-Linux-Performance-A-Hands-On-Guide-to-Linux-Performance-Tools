### 7.3\. Chapter Summary

This chapter provided information about how to use the Linux network performance tools to monitor the network traffic flowing through a system all the way from the low-level network interfaces to high-level applications. It introduced tools to query the current physical link settings (<tt>mii-tool</tt>, <tt>ethtool</tt>) and tools that monitor the amount and types of packets flowing through the low-level interfaces (<tt>ifconfig</tt>, <tt>ip</tt>, <tt>sar</tt>, <tt>gkrellm</tt>, <tt>iptraf</tt>, <tt>netstat</tt>, <tt>etherape</tt>). It then presented tools that display the different types of IP traffic (<tt>gkrellm</tt>, <tt>iptraf</tt>, <tt>netstat</tt>, <tt>etherape</tt>) and the amounts of each type of traffic (<tt>gkrellm</tt>, <tt>iptraf</tt>, <tt>etherape</tt>). This chapter then presented a tool (<tt>netstat</tt>) that maps the IP socket usage to the process that is receiving/sending each type of traffic. Finally, a network-visualization tool was presented that visualizes the relationship between the type and amount of data flowing through a network and which nodes it is flowing between (<tt>etherape</tt>).

The next chapters describe some of the common Linux tools that make using performance tools easier. They are not performance tools themselves, but they make using the performance tools more palatable. They can also help to visualize and analyze the results of the tools, as well as automate some of the more repetitive tasks.
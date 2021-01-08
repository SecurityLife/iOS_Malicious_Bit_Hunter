# iOS Malicious Bit Hunter
iOS Malicious Bit Hunter is a malicious plug-in detection engine for iOS applications. It can analyze the head of the macho file of the injected dylib dynamic library based on runtime, and can perform behavior analysis through interface input characteristics to determine the behavior of the dynamic library feature. The program does not rely on the jailbreak environment and can be used on the AppStore.

# What’s new feature : 
1. A new way to accurately identify the behavior of iOS malicious code will be introduced. This is a method of analyzing malicious code running in memory based on the Mach-O format within the App, which can execute flexible behavior recognize for analysis and continuous tracking. This is a very accurate anti-plug-in defense method, including behaviors, variants, and codes with strong obfuscate  (including ollvm), which has achieved very good results in our defense process.

2. In addition, we have integrated the assemble instruction-level security aspect capability in the engine to implement our defense ability. Through the security aspect capability, we can accurately identify the risks brought by malicious code, and through the union defense of the app and the cloud, we can accurately battle the malicious code to achieve a fine-grained defense effect, and even let the malicious code not affect the normal use of the app and let the code is invalid.

# Logic Priciple 
https://github.com/SecurityLife/iOS_Malicious_Bit_Hunter/wiki/Logic-Priciple

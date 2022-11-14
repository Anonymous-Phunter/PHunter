# Ground truth of samples
| **Index** | **Apk** | **TPL**<sup>*</sup> | **CVE** | **IsPatched** |  
|---|---|---|---|---|
| 1 | com.developerfromjokela.motioneyeclient.apk | okhttp:4.8.1 | CVE-2021-0341 | False  |  
| 2 | com.dougkeen.bart.apk | jackson-databind:2.6.1 | CVE-2019-14893 | False  |  
| 3 | com.greenaddress.abcore.apk | commons-compress:1.19 | CVE-2018-1324 | True  |  
| 4 | de.devmil.muzei.bingimageofthedayartsource.apk | retrofit:2.5.0 | CVE-2018-1000850 | True  | 
| 5 | de.danoeh.antennapod.apk | conscrypt-android:2.4.0 | CVE-2017-13309 | True  |  
| 6 | ch.abertschi.adfree.apk | xstream:1.4.7 | CVE-2017-7957 | False  |  
| 7 | ch.bailu.aat.apk | androidsvg:1.4 | CVE-2017-1000498 | True  |  
| 8 | com.nextcloud.client.apk | jackrabbit-webdav:2.13.1 | CVE-2016-6801 | False  |  
| 9 | com.adonai.manman.apk | jsoup:1.12.1 | CVE-2015-6748 | True  |  
| 10 | de.vier_bier.habpanelviewer.apk | netty:3.6.5.Final | CVE-2014-3488 | False |  

\* The TPL version in the table refers to the version used by the apk.  
\* The groundtruth is used for non-obfuscated apps, apps obfuscated by allatori and obfuscapk. For apps obfuscated by proguard and dasho, one should refer to the mapping file to check whether the patch related methods are deleted. Since the patch is not present if the patch related methods are removed during obfuscation.


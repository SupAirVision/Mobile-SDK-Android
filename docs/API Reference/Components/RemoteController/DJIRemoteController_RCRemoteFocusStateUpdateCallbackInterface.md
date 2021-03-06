<div class="article"><h1 ><font color="#AAA">class </font>FocusControllerStateCallback</h1></div>

~~~java
 interface FocusControllerStateCallback 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.remotecontroller</td></tr></table></html>



##### Description:



<font color="#666">Callback function that updates the Remote Focus State.



##### Class Members:



#### Callback Method

<div class="api-row" id="djiremotecontroller_updateremotefocusstate"><div class="api-col left">State</div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djiremotecontroller_updateremotefocusstate_inline">onUpdate</a></div></div><div class="inline-doc" id="djiremotecontroller_updateremotefocusstate_inline"

><div class="article"><h6 ><font color="#AAA">method </font>onUpdate</h6></div>

~~~java
        void onUpdate(@NonNull FocusControllerState remoteFocusState)
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.remotecontroller</td></tr></table></html>



##### Description:



<font color="#666">Callback function that updates the Remote Focus State, only support Focus product. If the isRCRemoteFocusCheckingSupported is <code>true</code>, this  callback function will be called.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">@NonNull <a href="/Components/RemoteController/DJIRemoteController_DJIRCRemoteFocusState.html#djiremotecontroller_djircremotefocusstate">FocusControllerState</a> <font color="#000">remoteFocusState</td><td><font color="#666"><i>Current state of the Remote Focus state.</i></td></tr></table></html></div>



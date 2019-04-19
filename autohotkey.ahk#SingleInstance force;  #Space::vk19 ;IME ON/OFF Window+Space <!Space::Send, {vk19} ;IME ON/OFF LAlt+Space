#SingleInstance force;

#Space::vk19 ;IME ON/OFF Window+Space
<!Space::Send, {vk19} ;IME ON/OFF LAlt+Space

#right::Send, ^{vk27} ;This will disable the effect of Win + ->
#left::Send, ^{vk25} ;This will disable the effect of Win + <-

<+#right::Send, ^+{vk27} ; Win+Shift+-> => Ctrl+Shift+->
<+#left::Send, ^+{vk25} ; Win+Shift+<- => Ctrl+Shift+<-

Alt::
KeyWait, Alt
return

LAlt Up::
if (A_PriorKey = "Alt")
	return
return

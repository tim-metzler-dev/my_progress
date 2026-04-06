# Day 43
Like Robert Kiyosaki said: "Your future is created by what you do today, not tomorrow."

## Today I learned:
1. To make subtitles and captions in HTML for video or audio, you can use the track element. It's inside the tag of video or audio.:
		 <track
		    src="captions.vtt"	<!-- This is the place where the text is. -->
		    kind="subtitles"  <!-- You define if these are subtitles or captions or chapters/ metadata. -->
		    srclang="en"	<!-- The language of your src. -->
		    label="English"/>   <!-- The label that will be shown with subtitle / caption… on. -->
	You can use services like veed.io, Rev, Amara, and Descript, to macke the vtt document of your video.
  If you macke the track element like this, you won't have subtitle or captions… by default. If you want them by default, you can write the default attribute inside the track element.
2. To make elements accessible with only a keyboard, you can use tabindex and accesskey. If you set the tabindex to 0 you can focus the element and it will be part of the default tab-order.
 If you set it to -1 you can't focus the element. You can add special orders with tabindex 1;2;3 and defining wich element is when in the tab-order.
 With accesskey you define a shortcut with that the element will be focused. For example accesskey="s" in a safe button. If you use that you can click ALT + S on windows or CTRL + Option + S on mac.
     

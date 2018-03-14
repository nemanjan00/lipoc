<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>LIPOC</title>
	</head>
	<body>
		<div id="local-ip"></div>

		<script src="jquery-3.3.1.slim.min.js"></script>

		<script type="text/javascript" charset="UTF-8">
			function checkLocal() {
				window.RTCPeerConnection = window.RTCPeerConnection || window.mozRTCPeerConnection || window.webkitRTCPeerConnection;	//compatibility for firefox and chrome
				var pc = new RTCPeerConnection({iceServers: []}), noop = function () {
				};

				console.log(pc);

				pc.createDataChannel("");	 //create a bogus data channel
				pc.createOffer(pc.setLocalDescription.bind(pc), noop);	  // create offer and set local description
				pc.onicecandidate = function (ice) {  //listen for candidate events
					if (!ice || !ice.candidate || !ice.candidate.candidate) return;
					var myIP = /([0-9]{1,3}(\.[0-9]{1,3}){3}|[a-f0-9]{1,4}(:[a-f0-9]{1,4}){7})/.exec(ice.candidate.candidate)[1];
					jQuery(document).ready(function () {
						jQuery("#local-ip").append("<li class=\"list-group-item\">Your Local IP is: " + myIP + "</li>");
						jQuery("#local-ip").show("slow");
					});

					pc.onicecandidate = noop;
				};
			}

			checkLocal();
		</script>
	</body>
</html>

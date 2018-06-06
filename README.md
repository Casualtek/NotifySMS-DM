# NotifySMS-DM
Notify incoming SMS to Asterisk via Direct Message on Twitter.

Based on the work of Jorge A. Duarte G. (babetoduarte) with <a href="https://github.com/babetoduarte/TweetNotify">TweetNotify</a>.

Requires chan_dongle for Asterisk. Requires Tweepy and Pyst2.
Requires a dedicated Twitter account to send the incoming SMS as direct messages.

Uses Python Base64 decoding for a more accurate conversion/transfer of incoming text messages than with the native Base64 decoding. 

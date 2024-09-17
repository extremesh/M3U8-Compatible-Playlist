[- Introduction -]
______________________________________________________________

This template / format should help with creating a single M3U8 playlist which would work on Kodi, Tivimate and others.

[- The Code -]
______________________________________________________________

#EXTINF:0 group-title="[title-here]" tvg-logo="[logo-here]", [stream-name]
#KODIPROP:inputstreamaddon=inputstream.adaptive
#KODIPROP:inputstream.adaptive.manifest_type=hls
#KODIPROP:inputstream.adaptive.mime_type=application/vnd.apple.mpegurl
https://[stream-url-here]

**replace tags in [] as needed.

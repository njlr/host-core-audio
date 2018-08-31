genrule(
  name = 'core-audio-framework', 
  out = 'CoreAudio.framework', 
  cmd = 'cp -r /System/Library/Frameworks/CoreAudio.framework $OUT', 
)

prebuilt_apple_framework(
  name = 'core-audio', 
  framework = ':core-audio-framework', 
  preferred_linkage = 'static', 
  visibility = [
    'PUBLIC', 
  ], 
)

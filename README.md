* 기본 기능
  - HTML5와 JavaScript code를 결합하여 한글과 영어 text를 읽어줄 수 있는 TTS기능을 제공합니다.
  - 텍스트는 Google 번역의 TTS 기능을 사용하여 오디오로 재생됩니다.
  - 페이지는 반응형이어서 browser의 크기에 따라 내부 요소들의 widget 크기를 조정합니다.

* Text 입력 및 준비작업
  - 첫 번째 version에서는 입력으로 text file을 loading하지만, 두 번째 version 부터는 아래쪽 text area에 사용자가 text를 직접 입력합니다.
  - 한 문장이 너무 길면 아래 text area에서 한번에 듣기 쉬운 단위로 나눌 수 있습니다.
  - 입력이 끝나면 'Load' button을 눌러 문장 또는 절 단위로 나누어 윗쪽 window에 정리합니다.

* TTS 사용 방법
  - 윗쪽 window에서 각 line을 click하면 TTS가 text를 읽어줍니다.
  - 사용자는 slider를 움직여 재생 속도를 조정할 수 있습니다.
  - Hot Keys: previous (z), current (x), next (c), slow (-), fast (=), stop (s)

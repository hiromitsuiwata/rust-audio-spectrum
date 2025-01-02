# rust-audio-spectrum

## 参考

- https://qiita.com/kamiro/items/5493dd109b7cc5043814
- https://github.com/RustAudio/cpal
- https://zenn.dev/yutannihilation/articles/bb89785ceaad77
- https://github.com/RustAudio/cpal/tree/master/examples

## 環境構築

```bash
sudo apt -y install alsa pulseaudio libasound2-dev pkg-config
export PULSE_SERVER=unix:$(sed 's/unix://g' <<< "$PULSE_SERVER")
```
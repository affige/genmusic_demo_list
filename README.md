A list of demo websites for automatic music generation research

[generate melody]
* [folkRNN](https://github.com/IraKorshunova/folk-rnn) (LSTM): https://folkrnn.org/
* [MidiNet](https://arxiv.org/abs/1703.10847) (CNN+GAN; yang17ismir): https://richardyang40148.github.io/TheBlog/midinet_arxiv_demo.html
* [StructureNet](http://ismir2018.ircam.fr/doc/pdfs/126_Paper.pdf) (LSTM; medeot18ismir) https://www.dropbox.com/sh/yxkxlnzi913ba50/AAA_mDbhdmaGJC9qj0zSlqCea?dl=0


[generate single-track polyphonic music]
* [BachProp](https://arxiv.org/abs/1812.06669) (GRU; colombo18arxiv): https://sites.google.com/view/bachprop
* [Modularized VAE](https://arxiv.org/pdf/1811.00162.pdf) (GRU+VAE; wang19icassp): https://github.com/MiuLab/MVAE_Music


[given chord, generate melody]
* [JazzGAN](http://musicalmetacreation.org/mume2018/proceedings/Trieu.pdf) (GAN; trieu18mume): https://www.cs.hmc.edu/~keller/jazz/improvisor/
* [XiaoIce Band](http://staff.ustc.edu.cn/~qiliuql/files/Publications/Hongyuan-Zhu-KDD2018.pdf) (GRU; zhu18kdd): http://tv.cctv.com/2017/11/24/VIDEo7JWp0u0oWRmPbM4uCBt171124.shtml


[generate drum]
* [DrumVAE](https://arxiv.org/abs/1902.03722) (GRU+VAE; thio19milc): http://vibertthio.com/drum-vae-client


[generate melody+chords (two tracks)]
* [LeadsheetGAN](https://arxiv.org/abs/1807.11161) (CRNN+GAN; liu18icmla): https://liuhaumin.github.io/LeadsheetArrangement/results
* [LeadsheetVAE](https://drive.google.com/file/d/10uGRGEI9IOfu_LyzDSG393fGhwUrEOi4/view) (RNN+VAE; liu18ismir-lbd): https://liuhaumin.github.io/LeadsheetArrangement/results


[generate melody, generate arrangement]
* LeadsheetGAN
* LeadsheetVAE
* XiaoIce Band (the "multi-instrument co-arrangement model")


[generate melody+bass+drum]
* [MusicVAE](https://arxiv.org/abs/1803.05428) (LSTM+VAE; roberts18icml): https://magenta.tensorflow.org/music-vae


[generate multitrack music]
* [MuseGAN](https://arxiv.org/abs/1709.06298) (CNN+GAN; dong18aaai): https://salu133445.github.io/musegan/
* [MIDI-VAE](https://arxiv.org/abs/1809.07600) (GRU+VAE; brunner18ismir): https://www.youtube.com/channel/UCCkFzSvCae8ySmKCCWM5Mpg
* [Multitrack MusicVAE](https://arxiv.org/abs/1806.00195) (LSTM+VAE; simon18ismir): https://magenta.tensorflow.org/multitrack


[given prime melody, generate melody+chords]
* [local_conv_music_generation](http://ouyangzhihao.com/wp-content/uploads/2018/12/MUSIC-GENERATION-WITH-LOCAL-CONNECTED-CONVOLUTIONAL-NEURAL-NETWORK.pdf) (CNN; ouyang18arxiv): https://somedaywilldo.github.io/local_conv_music_generation/


[given prime melody, generate melody+chords+bass]
* [BandNet](https://arxiv.org/abs/1812.07126) (RNN; zhou18arxiv): https://soundcloud.com/yichao-zhou-555747812/sets/bandnet-sound-samples-1 


[given piano score, generate an orchestration]
* [LOP](https://qsdfo.github.io/LOP/index.html) (RBM; crestel17smc): https://qsdfo.github.io/LOP/results.html


[symbolic-domain genre style transfer]
* [RaGAN](https://www.aaai.org/Papers/AAAI/2019/AAAI-LuC.2259.pdf) (GAN; lu19aaai): https://github.com/ChienYuLu/Play-As-You-Like-Timbre-Enhanced-Multi-modal-Music-Style-Transfer
* [CycleGAN](https://arxiv.org/pdf/1809.07575.pdf) (CNN+GAN; brunner18ictai): https://github.com/sumuzhao/CycleGAN-Music-Style-Transfer
* [FusionGAN](https://dac.cs.vt.edu/wp-content/uploads/2017/11/learning-to-fuse.pdf) (GAN; chen17icdm): http://people.cs.vt.edu/czq/publication/fusiongan/


[given score, generate musical audio (performance): Piano only]
* [PerformanceRNN](https://magenta.tensorflow.org/performance-rnn) (RNN): https://magenta.tensorflow.org/performance-rnn
* [VirtuosoNet](https://nips2018creativity.github.io/doc/virtuosonet.pdf) (LSTM+hierarchical attention network; jeong18nipsw): https://www.youtube.com/playlist?list=PLkIVXCxCZ08rD1PXbrb0KNOSYVh5Pvg-c
* [Wave2Midi2Wave](https://arxiv.org/abs/1810.12247) (transformer+wavenet; hawthorne19iclr): https://magenta.tensorflow.org/maestro-wave2midi2wave


[given score, generate musical audio (performance): Not limited to Piano]
* [PerformanceNet](https://arxiv.org/abs/1811.04357) (CNN+GAN; wang19aaai): https://github.com/bwang514/PerformanceNet


[audio synthesis]
* [GANSynth](https://arxiv.org/abs/1902.08710) (CNN+GAN; engel19iclr): https://magenta.tensorflow.org/gansynth
* [NSynth](https://arxiv.org/abs/1704.01279) (WaveNet; engel17arxiv): https://magenta.tensorflow.org/nsynth
* [WaveGAN](https://arxiv.org/abs/1802.04208) (CNN+GAN; donahue19iclr): https://github.com/chrisdonahue/wavegan
* [TFGAN](https://arxiv.org/abs/1902.04072) (CNN+GAN; marafioti19arxiv): https://tifgan.github.io/


[audio-domain singing style transfer]
* [cybegan](https://arxiv.org/pdf/1807.02254.pdf) (CNN+GAN; wu18faim): http://mirlab.org/users/haley.wu/cybegan/

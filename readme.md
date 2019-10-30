# Way of thinking

## Compression

video
> images type[array] + audio array
> > images autoencoder encode model
> > > image encode dataset + audio array

## reduction

image encode dataset + audio array
> image encode dataset autocoder decode model
> > images + audio
> > > video

## autoencoder

1080p
> 1920px * 1080px

### Encoder

input 1920 * 1080
> 2073600 array
> > 1036800 weight
> > > 518400 weight

### Decoder
> 518400 weight
> > 1036800 weight
> > > 2073600 array
> > > reshape 1920 * 1080

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
> 1920 * 1080 array
> > 2 * 2 * 959 * 539  weight
> > > 2 * 2 * 479 * 269 weight

### Decoder
> 2 * 2 * 479 * 269 weight
> > 2 * 2 * 959 * 539 weight
> > > 1920 * 1080 array

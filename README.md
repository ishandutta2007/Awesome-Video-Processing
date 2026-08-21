# Awesome-Video-Processing

Markdown
# Top Video Processing Ecosystem


**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Video Transcoding, Encoding, Transformation, Editing, Processing, Optimization, Streaming & Media APIs*  
**Last updated: August 2026**


This repository tracks notable **SaaS/Hosted Platforms** and **open-source projects** for **Video Processing**. These tools provide APIs, infrastructure, libraries, and platforms for video encoding, transcoding, resizing, compression, format conversion, editing, compositing, captioning, thumbnail generation, media analysis, adaptive bitrate packaging, streaming, and automated video creation.


**Examples** include Cloudinary, Imgix, Shotstack, Zencoder, Mux, Cloudflare Images, Filestack, Transloadit, Banuba, and api.video.


**Open-source emphasis**: The open-source ecosystem is particularly important in video processing because many commercial platforms are ultimately built around mature open technologies such as **FFmpeg, GStreamer, libavcodec, libavformat, OpenCV, ImageMagick, WebRTC, and various codec libraries**. This section therefore includes both complete self-hostable media platforms and lower-level building blocks that can be combined into custom video-processing infrastructure.


A useful distinction is that **video-processing platforms** provide hosted APIs and workflows, while **media frameworks and codecs** provide the underlying processing primitives. Some projects provide both.


Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.


## Table of Contents


- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Open-Source Video Processing Stack](#open-source-video-processing-stack)
- [Video Processing Building Blocks](#video-processing-building-blocks)
- [Important Video Processing Concepts](#important-video-processing-concepts)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)


## SaaS/Hosted Platforms


- **[Cloudinary](https://cloudinary.com/)**  
  Cloud-based image and video platform providing upload, storage, transformation, transcoding, optimization, AI processing, delivery, and programmable media APIs. Cloudinary's video platform supports dynamic transcoding, smart cropping, overlays, adaptive bitrate streaming, subtitles, and other automated transformations. 


- **[Imgix](https://www.imgix.com/)**  
  Real-time image and media processing platform focused on URL-based transformation, optimization, rendering, and delivery.


- **[Shotstack](https://shotstack.io/)**  
  Cloud video automation API that uses JSON timelines to programmatically edit, compose, render, and personalize videos at scale. Its APIs cover editing, hosted assets, and ingestion/processing. 


- **[Zencoder](https://zencoder.com/)**  
  Cloud video encoding API for automated transcoding, format conversion, encoding workflows, and large-scale media processing.


- **[Mux](https://www.mux.com/)**  
  Developer-focused video infrastructure platform covering video ingestion, encoding, storage, playback, streaming, and video analytics.


- **[Cloudflare Images](https://www.cloudflare.com/developer-platform/products/cloudflare-images/)**  
  Cloudflare's image/media infrastructure for image storage, transformation, optimization, and delivery. It can be combined with Cloudflare's broader media and streaming services.


- **[Filestack](https://www.filestack.com/)**  
  File and media processing platform providing upload, transformation, conversion, storage integration, and delivery APIs.


- **[Transloadit](https://transloadit.com/)**  
  Automated file and video processing platform using API-driven processing workflows. Its processing robots include video encoding, resizing, conversion, and watermarking. 


- **[Banuba](https://www.banuba.com/)**  
  Video and AR technology platform providing SDKs for video editing, effects, filters, face tracking, augmented reality, and user-generated video experiences.


- **[api.video](https://api.video/)**  
  Video API platform providing video upload, encoding, storage, playback, streaming, and programmable video infrastructure.


### Additional Major Hosted Video Processing Platforms
Recommended Open-Source Combinations

Simple Video Conversion

FFmpeg + MinIO + FastAPI

Good for basic upload, transcoding, compression, thumbnail generation, and media APIs.

Cloudinary-Style Self-Hosted Media Processing

Openinary + MinIO/S3 + FFmpeg + CDN

Useful for applications requiring URL-based transformations, media storage, caching, and self-hosted infrastructure.

Production Video API

FastAPI + FFmpeg + Redis/Celery + PostgreSQL + MinIO

Provides an API-driven architecture for asynchronous video-processing jobs.

Large-Scale Transcoding

Kubernetes + FFmpeg + Redis/Kafka + S3/MinIO + GPU workers

Useful for processing large volumes of videos in parallel.

Real-Time Video

MediaMTX + FFmpeg/GStreamer + WebRTC/HLS

Useful for camera ingestion, live streaming, protocol conversion, recording, and playback.

Low-Latency Streaming

MediaMTX/SRS/OvenMediaEngine + WebRTC + HLS

Useful for interactive and near-real-time video applications.

Programmatic Video Generation

Remotion + FFmpeg + Node.js + S3/MinIO

Useful for automatically generating personalized marketing, social, educational, and product videos.

AI Video Analytics

FFmpeg + OpenCV + MediaPipe/Ultralytics + GPU

Useful for object detection, tracking, face/pose analysis, scene analysis, moderation, and video intelligence.

Multimedia Processing Platform

GStreamer + FFmpeg + MediaMTX + MinIO + Kubernetes

A flexible foundation for building a broad self-hosted video infrastructure platform.

Maximum Open-Source Flexibility

Kubernetes + FFmpeg + GStreamer + MinIO + MediaMTX + Redis + PostgreSQL + OpenCV + Video.js

Provides independent control over storage, processing, encoding, streaming, APIs, analytics, and playback.

Video Processing Building Blocks
Video Ingestion

Video Upload

Multipart Upload

Resumable Upload

Direct-to-S3 Upload

HTTP Ingestion

RTMP Ingestion

RTSP Ingestion

SRT Ingestion

WebRTC Ingestion

Camera Ingestion

Screen Capture

Live Video Ingestion

Batch Video Ingestion

Transcoding

Video Transcoding

Video Encoding

Video Decoding

Format Conversion

Codec Conversion

Resolution Conversion

Frame Rate Conversion

Bitrate Conversion

Constant Bitrate

Variable Bitrate

Two-Pass Encoding

Hardware Encoding

GPU Encoding

CPU Encoding

Batch Transcoding

Distributed Transcoding

Video Editing

Trim

Cut

Crop

Resize

Scale

Rotate

Flip

Concatenate

Split

Overlay

Watermark

Text Overlay

Subtitles

Captions

Transitions

Filters

Color Correction

Color Grading

Audio Mixing

Audio Replacement

Background Music

Compositing

Chroma Key

Green Screen

Picture-in-Picture

Slow Motion

Time-Lapse

Frame Interpolation

Video Optimization

Video Compression

Bitrate Optimization

Per-Title Encoding

Per-Scene Encoding

Content-Aware Encoding

Adaptive Bitrate

Resolution Ladder

Encoding Ladder

Quality Optimization

VMAF Optimization

Bandwidth Optimization

Storage Optimization

CDN Optimization

Automatic Format Selection

Streaming

Live Streaming

Video-on-Demand

VOD

Low-Latency Streaming

Ultra-Low-Latency Streaming

Adaptive Bitrate Streaming

HLS

DASH

CMAF

WebRTC

RTMP

RTSP

SRT

WebTransport

MPEG-TS

LL-HLS

DASH-LL

Video Packaging

HLS Packaging

MPEG-DASH Packaging

CMAF Packaging

Segmenting

Fragmented MP4

MPEG-TS

Manifest Generation

Multi-Bitrate Packaging

Subtitle Packaging

Audio Track Packaging

DRM Packaging

Video Codecs

H.264 / AVC

H.265 / HEVC

AV1

VP8

VP9

VVC / H.266

MPEG-2

MPEG-4

Theora

ProRes

DNxHD

DNxHR

JPEG 2000

Audio Codecs

AAC

Opus

MP3

Vorbis

AC-3

E-AC-3

FLAC

PCM

ALAC

Containers

MP4

MOV

MKV

WebM

AVI

MPEG-TS

MPEG-PS

MXF

Ogg

3GP

Video Metadata

Media Metadata

EXIF

XMP

ID3

MediaInfo

FFprobe

Duration

Resolution

Frame Rate

Bitrate

Codec

Color Space

Color Primaries

HDR Metadata

Audio Channels

Subtitle Tracks

Video AI

Object Detection

Object Tracking

Face Detection

Face Recognition

Face Tracking

Pose Estimation

Human Detection

Scene Detection

Shot Detection

OCR

Video Classification

Action Recognition

Content Moderation

NSFW Detection

Logo Detection

Brand Detection

Visual Search

Video Embeddings

Multimodal Embeddings

Video Captioning

Video Summarization

Subtitles & Accessibility

Closed Captions

Open Captions

SRT

VTT

TTML

WebVTT

Automatic Transcription

Speech-to-Text

Translation

Caption Alignment

Subtitle Burning

Multi-Language Captions

Audio Description

Video Quality

VMAF

PSNR

SSIM

MS-SSIM

Video Quality Assessment

Perceptual Quality

Compression Artifacts

Banding

Blocking

Blurring

Ringing

Motion Artifacts

Hardware Acceleration

NVIDIA NVENC

NVIDIA NVDEC

Intel Quick Sync

AMD VCE

AMD VCN

Apple VideoToolbox

VA-API

Video4Linux

CUDA

OpenCL

Metal

GPU Transcoding

Media Infrastructure

FFmpeg

GStreamer

MediaMTX

SRS

OvenMediaEngine

WebRTC

MinIO

S3

Redis

Kafka

PostgreSQL

Kubernetes

Docker

CDN

Object Storage

Edge Processing

Distributed Workers

Job Queues

Video APIs

Video Upload API

Transcoding API

Encoding API

Video Editing API

Video Transformation API

Thumbnail API

Screenshot API

Caption API

Subtitle API

Streaming API

Playback API

Media Metadata API

Video Analysis API

Video Moderation API

Video AI API

Video Generation API

Video Applications

Video Hosting

Video CMS

Video CDN

Video-on-Demand

Live Streaming

Video Editing

Video Generation

Video Personalization

Video Advertising

Video Commerce

Video Analytics

Video Surveillance

Video Conferencing

E-Learning Video

UGC Video

Social Video

Marketing Video

Product Video

AI Video

Video Search

Video Archives

Developer Video Infrastructure

Video-as-a-Service

Video API

Media API

Programmable Video

Programmable Media

Serverless Video Processing

Cloud Transcoding

Self-Hosted Transcoding

Distributed Transcoding

GPU Transcoding

Edge Video Processing

Real-Time Video Processing

Batch Video Processing

Event-Driven Video Processing

Media Pipelines

Video Processing Workers

Important Video Processing Concepts

Video Transcoding

Video Encoding

Video Decoding

Media Processing

Video Transformation

Video Compression

Video Optimization

Video Rendering

Video Compositing

Non-Linear Editing

Programmatic Video

Automated Video Generation

Video Personalization

Dynamic Video

Video Templates

Timeline Rendering

Scene Composition

Frame Processing

Frame Extraction

Thumbnail Generation

Poster Frame

Sprite Sheets

Video Previews

Video Montage

Video Concatenation

Video Trimming

Video Cropping

Video Resizing

Video Rotation

Video Watermarking

Video Overlay

Video Filtering

Color Correction

Color Grading

Chroma Key

Green Screen

Motion Tracking

Object Tracking

Face Tracking

Scene Detection

Shot Detection

Keyframe Extraction

Video Summarization

Video Captioning

Video Transcription

Speech-to-Text

Subtitle Generation

Subtitle Translation

Automatic Dubbing

Audio Extraction

Audio Normalization

Audio Mixing

Audio Transcoding

Adaptive Bitrate

ABR

HLS

MPEG-DASH

CMAF

WebRTC

RTMP

RTSP

SRT

LL-HLS

Low-Latency Streaming

Ultra-Low-Latency Streaming

Live Streaming

Video-on-Demand

VOD

Video CDN

Video Delivery

Video Storage

Object Storage

Media Asset Management

Video CMS

Video API

Media API

Video-as-a-Service

Programmable Video

Cloud Transcoding

Self-Hosted Transcoding

Distributed Transcoding

GPU Transcoding

Hardware Encoding

Hardware Decoding

NVENC

NVDEC

VideoToolbox

Quick Sync

VA-API

VMAF

PSNR

SSIM

MS-SSIM

Content-Aware Encoding

Per-Title Encoding

Per-Scene Encoding

Bitrate Ladder

Resolution Ladder

Encoding Ladder

Constant Bitrate

Variable Bitrate

Two-Pass Encoding

H.264

H.265

HEVC

AV1

VP8

VP9

VVC

H.266

ProRes

DNxHD

DNxHR

MP4

MOV

MKV

WebM

MPEG-TS

CMAF

FFmpeg

GStreamer

OpenCV

MediaMTX

SRS

OvenMediaEngine

WebRTC

Media Servers

Media Routers

Streaming Servers

Video Players

Video.js

Shaka Player

hls.js

dash.js

Plyr

Clappr

Video AI

Video Computer Vision

Object Detection

Object Tracking

Video Classification

Action Recognition

Face Detection

Pose Estimation

OCR

Content Moderation

Video Embeddings

Multimodal Video

AI Video Generation

Text-to-Video

Image-to-Video

Video-to-Video

Generative Video

Diffusion Video Models

Video Understanding

Video Search

Video Retrieval

Video Analytics

QoE

Video Observability

Playback Analytics

Buffering

Rebuffering

Startup Time

Dropped Frames

Playback Failure

Bitrate Adaptation

CDN Optimization

Edge Video Processing

Media Workflow Automation

Video Processing Pipelines

Media Pipelines

Video Job Queues

Distributed Media Workers

Kubernetes Video Processing

Serverless Video Processing

Self-Hosted Video Infrastructure

Open-Source Video Processing

Open-Source Video APIs

Open-Source Video Platforms

Open-Source Video Codecs

Open-Source Media Servers

Open-Source Video Editors

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, official link or GitHub repository, 1–2 sentence description, and whether it is SaaS/Hosted or open-source.

For video-processing libraries, identify the primary processing capability.

For media servers, identify the supported protocols.

Clearly distinguish open-source, source-available, open-core, managed SaaS, and proprietary products.

Verify the current license before adding an open-source entry.

Prefer actively maintained repositories with meaningful documentation and recent development.

Do not describe a codec library as a complete video-processing platform.

Do not describe a video player as a video-processing engine.

Prefer projects that materially contribute to video processing, transcoding, encoding, editing, streaming, media APIs, video AI, or media infrastructure.

Submit a PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

The video-processing ecosystem changes rapidly.

Video-processing platforms, media servers, video editors, codecs, players, and computer-vision frameworks represent different layers of the video technology stack.

FFmpeg and GStreamer are foundational processing frameworks rather than complete hosted equivalents of Cloudinary or Mux.

MediaMTX, SRS, OvenMediaEngine, Janus, and similar projects primarily address streaming/media-server infrastructure rather than general-purpose video transformation.

Video.js, Shaka Player, hls.js, and dash.js are primarily playback technologies rather than video-processing engines.

Codec projects such as x264, x265, SVT-AV1, rav1e, dav1d, VVenC, and libvpx are low-level encoding/decoding components.

Open-source projects may have different licenses, governance models, hosted offerings, and enterprise editions. Always verify the current license before commercial deployment.

Video processing can be computationally expensive. Large-scale transcoding often requires careful CPU/GPU capacity planning, storage architecture, queue management, and CDN design.

Video quality and encoding efficiency depend heavily on the source material, codec, resolution, bitrate, frame rate, GOP structure, hardware, encoder settings, and target playback environment.

Adaptive bitrate streaming requires careful encoding ladders, segment configuration, packaging, origin infrastructure, and CDN delivery.

Self-hosted video infrastructure provides greater control but requires responsibility for storage, processing capacity, security, monitoring, scaling, backups, CDN configuration, and media delivery.

AI-based video processing can introduce significant GPU requirements and should be evaluated separately from conventional transcoding workloads.

Made for video engineers, media infrastructure engineers, streaming developers, AI engineers, content platforms, SaaS developers, broadcasters, and open-source developers.
Let's make video processing more open, programmable, scalable, efficient, and accessible.

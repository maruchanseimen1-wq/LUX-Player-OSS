# LUX Player — Open-source components

This repository provides the corresponding source code of the open-source libraries that the LUX Player Android app distributes in binary form.

It does not contain the LUX Player app's own source code.

## FFmpeg

LUX Player uses libraries from the [FFmpeg](https://ffmpeg.org/) project under the GNU Lesser General Public License version 2.1 (LGPLv2.1). FFmpeg is linked dynamically as shared libraries (`libavutil.so`, `libavcodec.so`, `libavformat.so`).

For each released app version, the matching source materials are attached to the [Releases](../../releases) of this repository:

- the unmodified FFmpeg source tarball that was used
- a statement of source changes (none, if unmodified)
- the configure lines and build scripts for each Android ABI
- SHA-256 checksums that tie the source to the libraries shipped in that app version

FFmpeg is not owned by the LUX Player developer. FFmpeg is a trademark of Fabrice Bellard, originator of the FFmpeg project. The license text is included in each source archive.

---

# LUX Player — オープンソース部品

このリポジトリは、Androidアプリ「LUX Player」がバイナリの形で配布しているオープンソースのライブラリについて、対応するソースコードを提供するためのものです。

LUX Player本体のソースコードは含みません。

## FFmpeg

LUX Playerは、[FFmpeg](https://ffmpeg.org/)プロジェクトのライブラリを、GNU劣等一般公衆利用許諾書 第2.1版（LGPLv2.1）の条件で使用しています。FFmpegは共有ライブラリ（`libavutil.so`、`libavcodec.so`、`libavformat.so`）として動的にリンクしています。

公開したアプリの版ごとに、対応する資材をこのリポジトリの[Releases](../../releases)に添付します。

- 使用したFFmpegのソース（変更していない上流のアーカイブ）
- ソースの変更点の記載（変更がない場合はその旨）
- Androidの各ABIのconfigureの設定と構築スクリプト
- ソースと、その版のアプリに含まれるライブラリを結び付けるSHA-256

FFmpegの権利はLUX Playerの開発者にはありません。ライセンスの本文は各ソース資材に含まれています。

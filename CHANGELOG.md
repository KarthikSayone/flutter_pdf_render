# 0.69.0

* allowAntialiasingIOS support.

## 0.68.0

* Update device_info version.

## 0.67.0

* PdfViewerController now supports viewRect, zoomRatio, visiblePages, and currentPageNumber.

## 0.66.2

* FIXED: SDK version requirement is not compatible to stable releases.

## 0.66.0

* Introducing PdfViewer that supports interactive pinch-zoom (#5); not yet complete but things just work well.

## 0.65.0

* Fixes PDF page rotation issue on iOS (#18)
* Fixes Y-axis flipping issue on iOS (#9)

## 0.64.1

* Update documents.
* BREAKING CHANGE: PdfDocument/PdfPage/PdfPageImage no longer have public constructors.

## 0.64.0

* Introducing faster and memory-friendly PdfPageImage rendering mechanism based on Pointer<Uint8> (dart:ffi).
* BREAKING CHANGE: backgroundFill/renderingPixelRatio/dontUseTexture are moved to PdfPageTextureBuilder.
* BREAKING CHANGE: PdfPageImage.image is replaced by PdfPageImage.pixels, PdfPageImage.createImageIfNotAvailable, createImageIfNotAvailable.imageIfAvailable.

## 0.63.0

* Introducing PdfDocumentLoader.onError to handle document open error (#17 by Sp4Rx).

## 0.62.0

* Minor bug fix.

## 0.61.0

* Introduces pdf_render_widgets2.dart. The classes in pdf_render_widgets.dart are deprecated now.

## 0.57.2

* Update pubspec.yaml not to be shown as WEB compatible on pub.dev (#11).

## 0.57.1

* Update comments (#6).

## 0.57.0

* On iOS Simulator, the plugin now uses compatibility rendering mode; to test the actual behavior, please use physical devices.

## 0.56.0

* Woops, backgroundFill must be true for default.

## 0.55.0

* Now render like functions treat null and 0 almost identical.

## 0.54.0

* PdfPage.render method does not handle w=0,h=0 case (Changes on 0.51.0 breaks compatibility with older versions).

## 0.53.0

* Introduces PdfPageFit to specify PDF page size fit rule easier.

## 0.51.0

* PdfPage.render method does not handle w=0,h=0 case.

## 0.49.0

* Just update documents. Also introduces `PdfPageImageTexture` class that is used internally to interact with Flutter's Texture class.

## 0.46.0

* `PdfPageView` uses Texture rather than RawImage.

## 0.37.0

* Introducing `PdfDocumentLoader` and `PdfPageView` that eases PDF view.

## 0.33.0

* FIXED: disposing PdfDocument may cause ArrayIndexOutOfBoundsException. (Android)

## 0.29.0

* Minor build configuration changes.

## 0.27.0

* Add backgroundFill option to render method.

## 0.23.0

* First version that supports Android.

## 0.1.0

* First release.

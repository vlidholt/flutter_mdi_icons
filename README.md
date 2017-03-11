# flutter_mdi_icons
Provides additional set of icons for Flutter. Icons are from materialdesignicons.com and released under open source licenses as listed here: https://github.com/Templarian/MaterialDesign

# Usage
Currently only working on this version of Flutter: https://github.com/vlidholt/flutter hoping to get the patch landed in main repo.

A. Add font in your project folder at: fonts/materialdesignicons-webfont.ttf

B. Add the following to your pubspec.yaml:

    fonts:
      - family: MDI
        fonts:
          - asset: fonts/materialdesignicons-webfont.ttf

C. Include the mdi_icons.dart file in your project

D. Create an icon from code like so:

    new Icon(MDIIcons.ghost);

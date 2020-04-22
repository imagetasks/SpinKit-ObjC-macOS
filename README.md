SpinKit-ObjC-macSO
============

macOS port of [SpinKit](https://github.com/tobiasahlin/SpinKit), based and inspired by [SpinKit-ObjC](https://github.com/raymondjavaxx/SpinKit-ObjC). Used by [Pixea - free image viewer for macOS](https://www.imagetasks.com/pixea/).



Usage
-----

Simply instantiate `RTSpinKitView` with the desired style and add to your view hierarchy.

    #import <SpinKit/RTSpinKitView.h>
    ...
    RTSpinKitView *spinner = [[RTSpinKitView alloc] initWithStyle:RTSpinKitViewStyleWave];
    [self.view addSubview:spinner];

Available styles:

* `RTSpinKitViewStylePlane`
* `RTSpinKitViewStyleCircleFlip`
* `RTSpinKitViewStyleBounce`
* `RTSpinKitViewStyleWave`
* `RTSpinKitViewStyleWanderingCubes`
* `RTSpinKitViewStylePulse`
* `RTSpinKitViewStyleChasingDots`
* `RTSpinKitViewStyleThreeBounce`
* `RTSpinKitViewStyleCircle`
* `RTSpinKitViewStyle9CubeGrid`
* `RTSpinKitViewStyleWordPress`
* `RTSpinKitViewStyleFadingCircle`
* `RTSpinKitViewStyleFadingCircleAlt`
* `RTSpinKitViewStyleArc`
* `RTSpinKitViewStyleArcAlt`

Acknowledgements
----------------

Animations based on [SpinKit](https://github.com/tobiasahlin/SpinKit) by [Tobias Ahlin](https://github.com/tobiasahlin).

Initial UIKit port [SpinKit-ObjC](https://github.com/raymondjavaxx/SpinKit-ObjC) by [Ramon Torres](https://github.com/raymondjavaxx).

[SpinKit Contributors](https://github.com/raymondjavaxx/SpinKit-ObjC/graphs/contributors).

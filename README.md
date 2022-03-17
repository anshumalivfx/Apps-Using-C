# Apps Using

- FUCK YOU BITCH
- DAMN ITS FOR TESTING

```objective-c
//
//  ViewController.m
//  CApp
//
//  Created by Anshumali Karna on 16/03/22.
//

#include "ViewController.h"
#include "NewViewController.h"

@interface ViewController ()
@property (weak, nonatomic) IBOutlet UILabel *label1;

@end

@implementation ViewController
- (IBAction)newPressed:(id)sender {

}
- (IBAction)buttonPressed:(id)sender {
    _label1.text = @"Hello World";
    _label1.textColor = [UIColor redColor];
}

- (void)viewDidLoad {
    [super viewDidLoad];
    // Do any additional setup after loading the view.
}


@end

```

#!/usr/bin/javascript
# -*- coding: utf-8 -*-

class About extends Me {
  public getCurrentWorkplace(): { workplace: { company: string; position: string } } {
    return {
      workplace: {
        company: 'Qquicker',
        position: 'Founder',
      },
    };
  }

  public getDailyKnowledge(): Array<string> {
    return [
      'Php',
      'Javascript',
      'Laravel',
      'Vuejs',
      'Angular',
      'ReactNative',
      'TailwindCss',
      'Aws',
    ];
  }

  public getFutureGoal(): string {
    return 'To contribute to open source.';
  }
}


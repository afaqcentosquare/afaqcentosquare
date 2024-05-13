## Hi there, I'm Muhammad Afaq 👋
```php
<?php

namespace MuhammadWaqas;

class About extends Me
{
  public function getBio(): string
  {
      return 'I am Muhammad Afaq, a web developer with over 8 years of experience,
              and a passion for crafting exceptional digital solutions.
              I develop modern technology web & mobile applications with popular frameworks like Laravel, Vue, React & React Native.
              SaaS,
              CMS,
              CRM
              Multi-Tenancy,
              E-Commerce,
              RestFull API
              I develop advanced software with software architectures.';
  }

  public function getMore(): array
  {
    return [
      'work' => [
        'Full Stack Developer - Upwork (August 2021 - Present)',
        'Full Stack Developer - CentoSquare (September 2018 - August 2021)',
        'Lead Developer - CentoSquare (June 2017 - August 2018)',
        'Junior Web Developer - CentoSquare (April 2016 - May 2017)',
        'Web Developer Internship - CentoSquare (January 2016 - March 2016)',
      ],
    ];
  }

  public function getCurrentState(): array
  {
    return [
      'working_on' => [
        'Laravel, Livewire, Filament, Vue.js, React.js & React Native',
      ],
      'learning' => [
        'Advanced Programming Techniques',
        'Goo Lang',
      ],
    ];
  }

  public function getFutureGoal(): string
  {
    return 'To contribute to open source.';
  }
}

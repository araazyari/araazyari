```php
namespace ArazYari

class About extends Me{
    public function getCurrentWorkspace() {
        return [
            'workplace'=>[
                'company' => 'Soha Sarmayeh Hooshmand Ayandeh (Pinvest)',
                'website' => 'https://pinvest.ir',
                'position' => 'PHP Backend Developer',
            ] 
        ];
    }
    
    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }
    
    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
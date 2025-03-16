<?php
namespace MayconMacedo;

class About extends Me
{
    public function getPersonalInfo(): array
    {
        return [
            'name'     => 'Maycon Macedo',
            'position' => 'Junior Full Stack Developer',
            'location' => 'Nova Friburgo, RJ - Brazil 🇧🇷',
        ];
    }
    public function getSkills(): array
    {
        return [
            'languages'  => ['Python', 'C#', 'JavaScript', 'HTML', 'CSS', 'PHP'],
            'frameworks' => ['React', 'React Native', 'Laravel', 'Docker', 'Nodejs', 'Angular', 'WordPress'],
            'databases'  => ['MySQL', 'PostgreSQL', 'Fauna']
        ];
    }
}

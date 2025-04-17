<script>

    import * as d3 from 'd3';

    // declare weekdays array
    let weekdays = [
            "Sunday", 
            "Monday", 
            "Tuesday", 
            "Wednesday", 
            "Thursday", 
            "Friday", 
            "Saturday"
    ];

    // declare course object
    const course = {id: 'ITCS 4122', name: 'Visual Analytics', students: 76};

    // declare courses (array of objects)
    let courses = [
        {id: 'ITCS 4122', name: 'Visual Analytics', students: 76},
        {id: 'ITCS 4156', name: 'ML', students: 60},
        {id: 'ITCS 2181', name: 'Computer Organization', students: 120}
    ];

    let circles = $state(
        [
            {r: 30, cx: 100, cy: 100, color: 'limegreen'},
            {r: 40, cx: 200, cy: 100, color: 'red'},
            {r: 50, cx: 300, cy: 100, color: 'yellow'},
            {r: 60, cx: 400, cy: 100, color: 'grey'},
            {r: 70, cx: 500, cy: 100, color: 'lavender'},
            {r: 80, cx: 600, cy: 100, color: 'skyblue'}
        ]
    );

    let chartFreq = $state(
        [
            {letter: "A", frequency: 0.08167},
            {letter: "B", frequency: 0.01492},
            {letter: "C", frequency: 0.02782},
            {letter: "D", frequency: 0.04253},
            {letter: "E", frequency: 0.12702},
            {letter: "F", frequency: 0.02288},
            {letter: "G", frequency: 0.02015},
            {letter: "H", frequency: 0.06094},
            {letter: "I", frequency: 0.06966},
            {letter: "J", frequency: 0.00153},
            {letter: "K", frequency: 0.00772},
            {letter: "L", frequency: 0.04025},
            {letter: "M", frequency: 0.02406},
            {letter: "N", frequency: 0.06749},
            {letter: "O", frequency: 0.07507},
            {letter: "P", frequency: 0.01929},
            {letter: "Q", frequency: 0.00095},
            {letter: "R", frequency: 0.05987},
            {letter: "S", frequency: 0.06327},
            {letter: "T", frequency: 0.09056},
            {letter: "U", frequency: 0.02758},
            {letter: "V", frequency: 0.00978},
            {letter: "W", frequency: 0.0236},
            {letter: "X", frequency: 0.0015},
            {letter: "Y", frequency: 0.01974},
            {letter: "Z", frequency: 0.00074}
        ]
    );

</script>


<div class="container mx-auto px-4 py-8 font-display">
    <h1 class="text-3xl font-bold text-center mb-4">
        Welcome to SvelteKit + D3.js Tutorial
    </h1>
    <h2 class="text-xl font-semibold text-center mb-6">
        Hello, Data Visualization World!
    </h2>
    <p class="text-center mb-8">
        This tutorial will guide you through creating interactive visualizations using 
        the power of SvelteKit and D3.js.
    </p>
</div>
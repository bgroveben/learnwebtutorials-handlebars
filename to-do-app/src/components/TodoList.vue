<template>
    <div>
        <ul>
        <li> Task A </li>
        <li> Task B</li>
        <li> Task C </li>
        </ul>
    </div>
</template>

<script type = "text/javascript" >

export default {
name: 'app',
components: {
TodoList,
},
props: ['todos'],
// Make data available to the template
data() {
return {
todos: [{
    title: 'Todo A',
    project: 'Project A',
    done: false,
}, {
    title: 'Todo B',
    project: 'Project B',
    done: true,
}, {
    title: 'Todo C',
    project: 'Project C',
    done: false,
}, {
    title: 'Todo D',
    project: 'Project D',
    done: false,
}],
};
},
};
</script>
<style>
</style>

<script lang="ts">
        const currentTime = new Date()
        const currentHour = currentTime.getHours()

        let greeting =""

        if (currentHour < 12) {
            greeting = "Good morning"
        } else if (currentHour <18){
            greeting = "Good evening"
        } else {
            greeting = "Good evening"
        }
</script>

<h1 class="text-3xl front-bold">{greeting}</h1>
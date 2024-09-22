<script>
    // You can import your picture from the static folder or a URL
    import profilePic from '/static/profilepic.jpg';
</script>

<section class="flex items-center justify-center min-h-screen">
    <div class="flex items-center w-3/4 rounded-lg overflow-hidden">
        <!-- Picture on the Left -->
        <div class="flex-shrink-0 h-full" style="border-right: 10px solid white;">
            <img
                    src={profilePic}
                    alt="Samuele"
                    class="h-full object-contain"
                    style="min-width: 200px; max-width: 300px;"
            />
        </div>

        <!-- Text on the Right -->
        <div class="text-center">
            <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=League+Spartan&size=50&duration=2000&pause=100&color=091E27&center=true&vCenter=true&multiline=true&width=1000&height=440&lines=Hi%2C+I+am+Samuele;and+welcome+to+my+website!;+;I+am+a+MsC+Student%2C+Software+Engineer;and+theoretical+computer+scientist" alt="Typing SVG" /></a>
        </div>
    </div>
</section>

<style>
    /* Optional: custom styles can be added here */
</style>



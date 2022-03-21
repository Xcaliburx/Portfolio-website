<template>
    <div class="contact py-5" id="contact">
        <h1 class=" text-center">Contact Me</h1>

        <form action="">
            <div class="form pt-5">
                <div class="name">
                    <h4 class="text-start">Your Name:</h4>
                    <input class="w-100 bg-secondary" type="text">
                </div>

                <div class="email mt-3">
                    <h4 class="text-start">Your Email Address:</h4>
                    <input class="w-100 bg-secondary" type="email">
                </div>

                <div class="description mt-3">
                    <h4 class="text-start">Description:</h4>
                    <textarea class="w-100 bg-secondary" name="description" rows="10"></textarea>
                </div>

                <button class="btn btn-primary mt-4 col-2">Submit</button>
            </div>
        </form>
    </div>
</template>

<style scoped>
    .form{
        padding-left: 200px;
        padding-right: 200px;
    }

    .contact{
        background-color: #1d1f21;
    }

    h1, h4, p{
        color: white;
    }
</style>
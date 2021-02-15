<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container">
            <a class="navbar-brand" href="#">
                <img src="../assets/img/vector-logo.png" height="100%">
            </a>
            <button class="navbar-toggler mb-4" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                        <form >
                        <input class="form-control" type="search" name="search" placeholder="Search">
                    </form>
                <ul class="nav nav-pills">
                    <li class="nav-item">
                        <router-link class="nav-link link tebel-sedang" to="/">Home &nbsp;&nbsp;</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link link tebel-sedang" to="#">About &nbsp;&nbsp;</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link link tebel-sedang" to="/login">Login &nbsp;&nbsp;</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link link tebel-sedang" to="#">Contact &nbsp;&nbsp;</router-link>
                    </li>
                    
                    <li class="nav-item">
                        <router-link class="nav-link active tebel-sedang rounded-pill bg-ungu shadow" to="/login">Sign Up</router-link>
                    </li>
                </ul>
            </div>
        </div>
        </nav>
    </div>
</template>

<script>
    export default {
        name: "Navbar",

        mounted() {
        
        },
    }
    </script>
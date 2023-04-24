<template>
<div class="container-fluid">
    <div class="row justify-content-center">
        <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2">
            <ul class="timeline timeline-centered">
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span></span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Event Title</h3>
                        <p>Nullam vel sem. Nullam vel sem. Integer ante arcu, accumsan a, consectetuer eget, posuere ut, mauris. Donec orci lectus, aliquam ut, faucibus non, euismod id, nulla. Donec vitae sapien ut libero venenatis faucibus. ullam dictum felis
                            eu pede mollis pretium. Pellentesque ut neque.</p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>March 23, 2016</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Event Title</h3>
                        <p>Nullam vel sem. Nullam vel sem. Integer ante arcu, accumsan a, consectetuer eget, posuere ut, mauris. Donec orci lectus, aliquam ut, faucibus non, euismod id, nulla. Donec vitae sapien ut libero venenatis faucibus. ullam dictum felis
                            eu pede mollis pretium. Pellentesque ut neque. </p>
                    </div>
                </li>
                <li class="timeline-item period">
                    <div class="timeline-info"></div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h2 class="timeline-title">April 2016</h2>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>April 02, 2016</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Event Title</h3>
                        <p>Nullam vel sem. Nullam vel sem. Integer ante arcu, accumsan a, consectetuer eget, posuere ut, mauris. Donec orci lectus, aliquam ut, faucibus non, euismod id, nulla. Donec vitae sapien ut libero venenatis faucibus. ullam dictum felis
                            eu pede mollis pretium. Pellentesque ut neque. </p>
                    </div>
                </li>
                <li class="timeline-item">
                    <div class="timeline-info">
                        <span>April 28, 2016</span>
                    </div>
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3 class="timeline-title">Event Title</h3>
                        <p>Nullam vel sem. Nullam vel sem. Integer ante arcu, accumsan a, consectetuer eget, posuere ut, mauris. Donec orci lectus, aliquam ut, faucibus non, euismod id, nulla. Donec vitae sapien ut libero venenatis faucibus. ullam dictum felis
                            eu pede mollis pretium. Pellentesque ut neque. </p>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.timeline-centered {
            @extend .timeline-split;
            @media (min-width: 992px) {
                &,
                .timeline-item,
                .timeline-info,
                .timeline-marker,
                .timeline-content {
                    display: block;
                    margin: 0;
                    padding: 0;
                }
                .timeline-item {
                    padding-bottom: 40px;
                    overflow: hidden;
                }
                .timeline-marker {
                    position: absolute;
                    left: 50%;
                    margin-left: -7.5px;
                }
                .timeline-info,
                .timeline-content {
                    width: 50%;
                }
                > .timeline-item:nth-child(odd) .timeline-info {
                    float: left;
                    text-align: right;
                    padding-right: 30px;
                }
                > .timeline-item:nth-child(odd) .timeline-content {
                    float: right;
                    text-align: left;
                    padding-left: 30px;
                }    
                > .timeline-item:nth-child(even) .timeline-info {
                    float: right;
                    text-align: left;
                    padding-left: 30px;
                }
                > .timeline-item:nth-child(even) .timeline-content {
                    float: left;
                    text-align: right;
                    padding-right: 30px;
                }
                > .timeline-item.period .timeline-content {
                    float: none;
                    padding: 0;
                    width: 100%;
                    text-align: center;
                }
                .timeline-item.period {
                    padding: 50px 0 90px;
                }
                .period .timeline-marker:after {
                    height: 30px;
                    bottom: 0;
                    top: auto;
                }
                .period .timeline-title {
                    left: auto;
                }
            }
        }
        .timeline {
        line-height: 1.4em;
        list-style: none;
        margin: 0;
        padding: 0;
        width: 100%
        }
        h1, h2, h3, h4, h5, h6 {
            line-height: inherit;
        }
</style>
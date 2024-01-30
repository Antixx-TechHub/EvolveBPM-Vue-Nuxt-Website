<template>
    <div class="clients-section pad-tb">
        <div class="container">
            <div class="row justify-content">
                <div class="col-lg-8">
                    <div class="common-heading text-l">
                        <h2 class="mb-4">Certifications</h2>
                    </div>
                </div>
            </div>
            <div class="row pb50 pt20">
                <div class="col-lg-12">
                    <div class="opl">
                        <ul class="list-unstyled d-flex justify-content-between">
                            <carousel :autoplay="true" :loop="true" :paginationEnabled="false"
                                :perPageCustom="[[0, 2], [576, 3], [768, 3], [1200, 4]]">
                                <slide>
                                    <div class="clients-logo"><img src="~/assets/images/client/clients-1.png" alt="text"
                                            class="img-fluid" /></div>
                                </slide>

                                <slide>
                                    <div class="clients-logo"><img src="~/assets/images/client/clients-2.png" alt="text"
                                            class="img-fluid" /></div>
                                </slide>
                                <slide>
                                    <div class="clients-logo"><img src="~/assets/images/client/clients-3.png" alt="text"
                                            class="img-fluid" /></div>
                                </slide>
                                <slide>
                                    <div class="clients-logo"><img src="~/assets/images/client/clients-4.png" alt="text"
                                            class="img-fluid" /></div>
                                </slide>
                                <slide>
                                    <div class="clients-logo"><img src="~/assets/images/client/clients-5.png" alt="text"
                                            class="img-fluid" /></div>
                                </slide>
                            </carousel>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="row justify-content">
                <div class="col-lg-8">
                    <div class="common-heading text-l">
                        <h2 class="mb-4">Awards</h2>
                    </div>
                </div>
            </div>
            <div class="row pt20">
                <div class="col-lg-12">
                    <div class="opl">
                        <ul class="list-unstyled d-flex justify-content-between">
                            <ul class="list-unstyled d-flex justify-content-between">
                                <carousel :autoplay="true" :loop="true" :paginationEnabled="false"
                                    :perPageCustom="[[0, 2], [576, 3], [768, 3], [1200, 4]]">
                                    <slide>
                                        <div class="clients-logo"><img src="~/assets/images/client/awd-one.png" alt="text"
                                                class="img-fluid" /></div>
                                    </slide>

                                    <slide>
                                        <div class="clients-logo"><img src="~/assets/images/client/awd-2.png" alt="text"
                                                class="img-fluid" /></div>
                                    </slide>
                                    <slide>
                                        <div class="clients-logo"><img src="~/assets/images/client/awd-3.png" alt="text"
                                                class="img-fluid" /></div>
                                    </slide>
                                    <slide>
                                        <div class="clients-logo"><img src="~/assets/images/client/awd-4.png" alt="text"
                                                class="img-fluid" /></div>
                                    </slide>
                                    <slide>
                                        <div class="clients-logo"><img src="~/assets/images/client/awd-one.png" alt="text"
                                                class="img-fluid" /></div>
                                    </slide>
                                </carousel>
                            </ul>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
    
<script>

import axios from 'axios'

export default {
    name: 'OurClients',
}
</script>
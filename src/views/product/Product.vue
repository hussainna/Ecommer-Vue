<template>
    <section class="product">
        <div class="container">
            <div class="title">
                <label>-- Organic Products --</label>
                <h2>All Organic Products</h2>
            </div>
            <div class="row">
                <div class="item">
                    <img src="../../assets/images/top-product-1.png" alt="">
                    <div class="item-bottom">
                        <div class="icons">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <h4>Key Line</h4>
                        <div class="price">
                            <label class="old-price">$70.00</label>
                            <label class="new-price">$90.00</label>
                        </div>
                        <button>Shop Now</button>
                    </div>
                </div>
                <div class="item">
                    <img src="../../assets/images/top-product-3.png" alt="">
                    <div class="item-bottom">
                        <div class="icons">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <h4>Fresh Watrenlean</h4>
                        <div class="price">
                            <label class="old-price">$20.00</label>
                            <label class="new-price">$90.00</label>
                        </div>
                        <button>Shop Now</button>
                    </div>
                </div>
                <div class="item">
                    <img src="../../assets/images/top-product-4.png" alt="">
                    <div class="item-bottom">
                        <div class="icons">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <h4>Visual matches </h4>
                        <div class="price">
                            <label class="old-price">$70.00</label>
                            <label class="new-price">$43.00</label>
                        </div>
                        <button>Shop Now</button>
                    </div>
                </div>
                <div class="item">
                    <img src="../../assets/images/top-product-5.png" alt="">
                    <div class="item-bottom">
                        <div class="icons">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <h4>Pomagranate Fruit</h4>
                        <div class="price">
                            <label class="old-price">$70.00</label>
                            <label class="new-price">$80.00</label>
                        </div>
                        <button>Shop Now</button>
                    </div>
                </div>

                <div class="item">
                    <img src="../../assets/images/top-product-6.png" alt="">
                    <div class="item-bottom">
                        <div class="icons">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <h4>Red onion</h4>
                        <div class="price">
                            <label class="old-price">$70.00</label>
                            <label class="new-price">$85.00</label>
                        </div>
                        <button>Shop Now</button>
                    </div>
                </div>
                <div class="item">
                    <img src="../../assets/images/top-product-7.png" alt="">
                    <div class="item-bottom">
                        <div class="icons">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <h4>Lens Results Broccoli</h4>
                        <div class="price">
                            <label class="old-price">$70.00</label>
                            <label class="new-price">$80.00</label>
                        </div>
                        <button>Shop Now</button>
                    </div>
                </div>
                <div class="item">
                    <img src="../../assets/images/top-product-8.png" alt="">
                    <div class="item-bottom">
                        <div class="icons">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <h4>Lens Results Spinach</h4>
                        <div class="price">
                            <label class="old-price">$70.00</label>
                            <label class="new-price">$80.00</label>
                        </div>
                        <button>Shop Now</button>
                    </div>
                </div>
                <div class="item">
                    <img src="../../assets/images/top-product-2.png" alt="">
                    <div class="item-bottom">
                        <div class="icons">
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                        </div>
                        <h4>Fresh Orangey</h4>
                        <div class="price">
                            <label class="old-price">$70.00</label>
                            <label class="new-price">$80.00</label>
                        </div>
                        <button>Shop Now</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name:'product',
        data(){
            return{
                classs:'item',
            }

        }
    }
</script>

<style lang="scss" scoped>
@import './product.scss'
</style>
<template>
  <div class="home">
    <van-swipe :autoplay="3000" indicator-color="white">
      <van-swipe-item>
        <img
            src="https://haitao.nosdn1.127.net/b9befc3e-a588-4c03-aefe-f1561c591849T1908231712_960_480.jpg?imageView&thumbnail=750x0&quality=95"
            width="100%" alt="">
      </van-swipe-item>
      <van-swipe-item>
        <img
            src="https://haitao.nosdn1.127.net/ba3da181-74ac-48a2-9b16-509758ae0a9cT1909201611_960_480.jpg?imageView&thumbnail=750x0&quality=95"
            width="100%" alt="">
      </van-swipe-item>
      <van-swipe-item>
        <img
            src="https://haitao.nosdn1.127.net/21a02a59-10a5-4ffd-8155-8341fb2772c2T1909201601_960_480.jpg?imageView&thumbnail=750x0&quality=95"
            width="100%" alt="">
      </van-swipe-item>
      <van-swipe-item>
        <img
            src="https://haitao.nosdn1.127.net/2bf8085d-39be-4816-8ef3-a0292f600771T1909201715_960_480.jpg?imageView&thumbnail=750x0&quality=95"
            width="100%" alt="">
      </van-swipe-item>
    </van-swipe>

    <form action="/">
      <van-search v-model="value"
                  placeholder="搜索汤臣倍健领券立减100元"
                  error
                  left-icon=""
                  right-icon="search"/>
    </form>

    <van-grid :column-num="5" :border="false">
      <van-grid-item icon="photo-o" text="充值中心"/>
      <van-grid-item icon="photo-o" text="火车票"/>
      <van-grid-item icon="photo-o" text="电影票"/>
      <van-grid-item icon="photo-o" text="酒店"/>
      <van-grid-item icon="photo-o" text="全部商品"/>
    </van-grid>

    <van-row>
      <van-col span="12">
        <img src="https://haitao.nosdn2.127.net/7e82c2f6-b67b-4a70-9cce-bedf1cd7d45aT1909201724_480_480.gif" alt=""
             width="100%" height="100%">
      </van-col>
      <van-col span="12">
        <van-row>
          <van-col span="24">
            <img src="https://haitao.nosdn2.127.net/72a3b88f-118a-47d2-8c7e-d0ebe6d774f6T1909201725_480_240.gif" alt=""
                 width="100%">
          </van-col>
        </van-row>
        <van-row>
          <van-col span="24">
            <img src="https://haitao.nosdn2.127.net/e5704da8-bfcc-4c0d-a2d4-0aa6323f1b87T1909201725_480_240.gif" alt=""
                 width="100%">
          </van-col>
        </van-row>
      </van-col>
    </van-row>

    <van-card price="20.00"
              desc="现代人熬夜追剧、加班，眼睛处在极度疲惫的状态，急需要越橘叶黄素片来让眼睛放松，每天两次，满足人体所需，营养成分直达眼部，吸收更彻底。"
              title="【护眼专家】考拉"
              thumb="https://haitao.nosdn2.127.net/7ad6e3d2fcbe4a1b8187a20430f905841568616612345k0m1twbi10834.jpg?imageView&thumbnail=404x404&quality=95&type=webp">
      <template slot="footer">
        <van-button type="danger" size="mini">去抢购</van-button>
      </template>
    </van-card>
    <van-card price="20.00"
              desc="现代人熬夜追剧、加班，眼睛处在极度疲惫的状态，急需要越橘叶黄素片来让眼睛放松，每天两次，满足人体所需，营养成分直达眼部，吸收更彻底。"
              title="【护眼专家】考拉"
              thumb="https://haitao.nosdn2.127.net/7ad6e3d2fcbe4a1b8187a20430f905841568616612345k0m1twbi10834.jpg?imageView&thumbnail=404x404&quality=95&type=webp">
      <template slot="footer">
        <van-button type="danger" size="mini">去抢购</van-button>
      </template>
    </van-card>
    <van-card price="20.00"
              desc="现代人熬夜追剧、加班，眼睛处在极度疲惫的状态，急需要越橘叶黄素片来让眼睛放松，每天两次，满足人体所需，营养成分直达眼部，吸收更彻底。"
              title="【护眼专家】考拉"
              thumb="https://haitao.nosdn2.127.net/7ad6e3d2fcbe4a1b8187a20430f905841568616612345k0m1twbi10834.jpg?imageView&thumbnail=404x404&quality=95&type=webp">
      <template slot="footer">
        <van-button type="danger" size="mini">去抢购</van-button>
      </template>
    </van-card>
    <van-card price="20.00"
              desc="现代人熬夜追剧、加班，眼睛处在极度疲惫的状态，急需要越橘叶黄素片来让眼睛放松，每天两次，满足人体所需，营养成分直达眼部，吸收更彻底。"
              title="【护眼专家】考拉"
              thumb="https://haitao.nosdn2.127.net/7ad6e3d2fcbe4a1b8187a20430f905841568616612345k0m1twbi10834.jpg?imageView&thumbnail=404x404&quality=95&type=webp">
      <template slot="footer">
        <van-button type="danger" size="mini">去抢购</van-button>
      </template>
    </van-card>
  </div>
</template>

<script>

  export default {
    name: 'home'
  }
</script>

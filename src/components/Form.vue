.<template>
  <div class="form-wraper" :class="{'show':isShow}">
      <div class="form-content">
            <div class="form-header">
                <div class="left-header item-center">
                    <h1>Thông tin nhân viên</h1>
                    <label for="" class="checkbox-label">
                        <input type="checkbox" name="" id="">
                        Là khách hàng
                    </label>
                    <label for="" class="checkbox-label">
                        <input type="checkbox" name="" id="">
                        Là khách hàng
                    </label>
                </div>
                <div class="right-header">
                    <div class="pop-up-close">
                        <i class="material-icons" v-on:click="function(){isShow = false}">
                            close
                        </i>
                        <i class="material-icons">
                            help_outline
                        </i>
                    </div>
                </div>
            </div>
            <div class="content-wraper">
                <div class="head-content">
                    <div class="head-content-left">
                        <div class="input-row d-flex">
                            <div class="short_length">
                                <div class="title-input">
                                    Mã <p> *</p>
                                </div>
                                <input type="text" name="" id="">
                            </div>
                            <div class="nor_length">
                                <div class="title-input">
                                    Tên <p> *</p>
                                </div>
                                <input type="text" name="" id="">
                            </div>
                        </div>
                        <div class="input-row">
                            <div class="max_length">
                                <div class="title-input">
                                    Đơn vị<p>*</p>
                                </div>
                                <input type="text" name="" id="">
                            </div>
                        </div>
                        <div class="input-row">
                            <div class="max_length">
                                <div class="title-input">
                                    Chức danh <p></p>
                                </div>
                                <input type="text" name="" id="">
                            </div>
                        </div>
                    </div>
                    <div class="head-content-right">
                        <div class="input-row d-flex">
                            <div class="short_length">
                                <div class="title-input">
                                    Ngày sinh
                                </div>
                                <input type="text" name="" id="">
                            </div>
                            <div class="nor_length">
                                <div class="title-input">
                                    Giới tính
                                </div>
                                <input type="text" name="" id="">
                            </div>
                        </div>
                        <div class="input-row d-flex">
                            <div class="nor_length">
                                <div class="title-input">
                                    Số CMND
                                </div>
                                <input type="text" name="" id="">
                            </div>
                            <div class="short_length">
                                <div class="title-input">
                                    Ngày cấp
                                </div>
                                <input type="text" name="" id="">
                            </div>
                        </div>
                         <div class="input-row">
                            <div class="max_length">
                                <div class="title-input">
                                    Nơi cấp <p></p>
                                </div>
                                <input type="text" name="" id="">
                            </div>
                        </div>
                    </div>
                </div>
                <div class="bottom-content">
                    <div class="input-row">
                        <div class="max_length">
                            <div class="title-input">
                                Địa chỉ<p></p>
                            </div>
                            <input type="text" name="" id="">
                        </div>
                    </div>
                    <div class="input-row d-flex">
                            <div class="small_length">
                                <div class="title-input">
                                    ĐT di động 
                                </div>
                                <input type="text" name="" id="">
                            </div>
                            <div class="small_length">
                                <div class="title-input">
                                    ĐT cố định 
                                </div>
                                <input type="text" name="" id="">
                            </div>
                            <div class="small_length">
                                <div class="title-input">
                                    Email 
                                </div>
                                <input type="text" name="" id="">
                            </div>
                    </div>
                    <div class="input-row d-flex">
                            <div class="small_length">
                                <div class="title-input">
                                    Tài khoản ngân hàng
                                </div>
                                <input type="text" name="" id="">
                            </div>
                            <div class="small_length">
                                <div class="title-input">
                                    Tên ngân hàng
                                </div>
                                <input type="text" name="" id="">
                            </div>
                            <div class="small_length">
                                <div class="title-input">
                                    Chi nhánh 
                                </div>
                                <input type="text" name="" id="">
                            </div>
                    </div>
                </div>
                <div class="form-footer d-flex">
                    <button class="btn btn-white">
                        <div class="btn-text">Hủy</div>
                    </button>
                    <div class="right-btn item-center">
                        <button class="btn btn-white">
                            <div class="btn-text">Cất</div>
                        </button>
                        <button class="btn btn-green">
                            <div class="btn-text">Cất và thêm</div>
                        </button>
                    </div>
                </div>
            </div>
            
      </div>
  </div>
</template>

<script>

export default {
data(){
    return{
        employee:null,
        isShow:true,
    }
}
}
</script>

<style scoped>
@import "../assets/style/Form.css";

</style>
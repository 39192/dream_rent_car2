<script>

</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-lg-3">
                <br>
                <div class="list-group">
                    <div class="list-group-item">
                        <h6>픽업일자</h6>
                        <div class="input-group date pickup-date">
                            <input class="form-control input-group-addon" id="pickup-date" readonly="">
                        </div>
                    </div>
                    <div class="list-group-item">
                        <h6>픽업시간</h6>
                        <select class="form-control" id="pickup-time">
                        </select>
                    </div>
                    <div class="list-group-item">
                        <h6>반납일자</h6>
                        <div class="input-group date return-date">
                            <input class="form-control input-group-addon" id="return-date" readonly="">
                        </div>
                    </div>
                    <div class="list-group-item">
                        <h6>반납시간</h6>
                        <select class="form-control" id="return-time">
                        </select>
                    </div>
                    <div class="list-group-item" style="background-color: #F5F5F5">
                        <div>렌트기간</div>
                        <div align="center">
                            <b id="rentDays" style="font-size: 18px; text-align: right;">1 일</b>
                        </div>
                    </div>
                </div>
                <br>
            </div>
            <!-- /.col-lg-3 -->
            <div class="col-lg-9">
                <br>
                <div class="info-sentence">
                    * 견적계산기는 렌트 비용 참고용입니다. 자세한 내용은 <b><a href="https://cafe.naver.com/guamfree/2766949"
                                                         style="color: rgb(107, 144, 220)" target="_blank"><u>벨류렌터카 예약안내</u></a></b> 에서 확인해주세요.
                </div>
                <div class="info-sentence">
                    * 추가 문의는 메일로 송부바랍니다. &lt; <b><a href="mailto:tillpark3@naver.com" style="color: rgb(107, 144, 220)"
                                                    target="_blank"><u>tillpark3@naver.com</u></a></b> &gt;
                </div>
                <br>
                <!-- 컴팩트 (5인) -->
                <hr>
                <h4 class="title-car">컴팩트 (5인)&nbsp;&nbsp;<small>리오급</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th class="vertical-align-middle" style="width:50%;" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="compact-basic-below-three-days">$37.0</div>
                        </td>
                        <td id="compact-zdc-td" colspan="2">
                            <div id="compact-zdc-below-three-days">$54.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="compact-basic-reservation">$10.0</td>
                        <td id="compact-basic-office">$37.0</td>
                        <td id="compact-zdc-reservation">$10.0</td>
                        <td id="compact-zdc-office">$44.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>
                <!-- 미드사이즈 (5인) -->
                <hr>
                <h4 class="title-car">미드 (5인)&nbsp;&nbsp;<small>마쯔다3급</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="midSize2-basic-below-three-days">$41.0</div>
                        </td>
                        <td id="midSize2-zdc-td" colspan="2">
                            <div id="midSize2-zdc-below-three-days">$63.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="midSize2-basic-reservation">$10.0</td>
                        <td id="midSize2-basic-office">$41.0</td>
                        <td id="midSize2-zdc-reservation">$10.0</td>
                        <td id="midSize2-zdc-office">$53.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>
                <!-- SUV (5인) -->
                <hr>
                <h4 class="title-car">SUV (5인)&nbsp;&nbsp;<small>셀토스급</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="suv-basic-below-three-days">$50.0</div>
                        </td>
                        <td id="suv-zdc-td" colspan="2">
                            <div id="suv-zdc-below-three-days">$72.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="suv-basic-reservation">$10.0</td>
                        <td id="suv-basic-office">$50.0</td>
                        <td id="suv-zdc-reservation">$10.0</td>
                        <td id="suv-zdc-office">$62.0</td>
                    </tr>
                    </tbody>
                </table>
                <br>
                <!-- 8인승 밴 (5인) -->
                <!--<hr>
                <h4 class="title-car">VAN(7/8인)&nbsp;&nbsp;<small>카니발급</small></h4>
                <h6 class="title-rate">카페요금</h6>
                <table class="table table-bordered">
                    <thead>
                    <tr>
                        <th style="width:50%" colspan="2">기본요금</th>
                        <th style="width:50%" colspan="2">기본요금 + 추가보험(ZDC)</th>
                    </tr>
                    </thead>
                    <tbody>
                    <tr>
                        <td colspan="2">
                            <div id="eightVan-basic-below-three-days">$80.0</div>
                        </td>
                        <td id="eightVan-zdc-td" colspan="2">
                            <div id="eightVan-zdc-below-three-days">$107.0</div>
                        </td>
                    </tr>
                    <tr>
                        <th>예약금액</th>
                        <th>현장지불</th>
                        <th>예약금액</th>
                        <th>현장지불</th>
                    </tr>
                    <tr>
                        <td id="eightVan-basic-reservation">$10.0</td>
                        <td id="eightVan-basic-office">$80.0</td>
                        <td id="eightVan-zdc-reservation">$10.0</td>
                        <td id="eightVan-zdc-office">$97.0</td>
                    </tr>
                    </tbody>
                </table>-->
                <br>
                <br><br><br>
                <!-- /.row -->
            </div>
            <!-- /.col-lg-9 -->
        </div>
        <!-- /.row -->
    </div>
</template>

<style scoped>

</style>

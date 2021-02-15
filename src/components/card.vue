<template>
    <div class="categories">
        <div class="col-xs-12">
            <div class="container">
                <div class="momentCard-header">
                    <h2 class="momentCard-title">Photography for Every Milestone</h2>
                    <div class="momentCard-subtitle">
                        Get inspired to create your own beautiful moments!
                    </div>
                </div>
                <div class="momentCard-wrapper row">
                    <div class="MomentCard__Container col-lg-3 col-md-4 col-xs-6">
                        <div class="MomentCard__ImageBackground">
                            <img class="b-lazy Image b-error" src="https://cdn.sweetescape.com/images/occasions/thumbnail/square/135/6d0b4e9a-be0d-4337-985a-eec772826920.jpg">
                        </div>
                        <div class="MomentCard__Text">
                            <div class="MomentCard__CardTitle">Holiday</div>
                            <div class="MomentCard__CardDescription">Capture precious moments at your favourite destinations</div>
                        </div>
                        <div class="MomentCard__CardArrow">
                            <img src="https://cdn.sweetescape.com/misc/svg/ico_arrow_right_black.svg">
                        </div>
                    </div>

                    <div class="MomentCard__Container col-lg-3 col-md-4 col-xs-6">
                        <div class="MomentCard__ImageBackground">
                            <img class="b-lazy Image b-error" src="https://cdn.sweetescape.com/images/occasions/thumbnail/square/136/8cc4fa2e-3a8c-41e5-994d-752cd8759738.jpg">
                        </div>
                        <div class="MomentCard__Text">
                            <div class="MomentCard__CardTitle">Family</div>
                            <div class="MomentCard__CardDescription">From intimate family shoots to special gatherings</div>
                        </div>
                        <div class="MomentCard__CardArrow">
                            <img src="https://cdn.sweetescape.com/misc/svg/ico_arrow_right_black.svg"></div>
                    </div>

                    <div class="MomentCard__Container col-lg-3 col-md-4 col-xs-6">
                        <div class="MomentCard__ImageBackground">
                            <img class="b-lazy Image b-error" src="https://cdn.sweetescape.com/images/occasions/thumbnail/square/142/a5822fb2-020f-4039-b9bd-c7d41dba03be.jpg">
                        </div>
                            <div class="MomentCard__Text">
                                <div class="MomentCard__CardTitle">Marriage</div>
                                <div class="MomentCard__GroupLink">
                                    <div class="MomentCard__TitleRow">
                                        <div class="MomentCard__ChildTitle">Proposal</div>
                                        <div class="MomentCard__ArrowInside">
                                            <img src="https://cdn.sweetescape.com/misc/svg/ico_arrow_right_black.svg">
                                        </div>
                                    </div>
                                    <div class="MomentCard__TitleRow">
                                        <div class="MomentCard__ChildTitle">Pre-wedding</div>
                                        <div class="MomentCard__ArrowInside">
                                            <img src="https://cdn.sweetescape.com/misc/svg/ico_arrow_right_black.svg">
                                        </div>
                                    </div>
                                    <div class="MomentCard__TitleRow">
                                        <div class="MomentCard__ChildTitle">Wedding</div>
                                        <div class="MomentCard__ArrowInside">
                                            <img src="https://cdn.sweetescape.com/misc/svg/ico_arrow_right_black.svg">
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="MomentCard__CardArrow">
                                <img src="https://cdn.sweetescape.com/misc/svg/ico_arrow_right_black.svg">
                            </div>
                        </div>

                    <div class="MomentCard__Container col-lg-3 col-md-4 col-xs-6"><div class="MomentCard__ImageBackground"><img class="b-lazy Image b-error" src="https://cdn.sweetescape.com/images/occasions/thumbnail/square/139/83a49867-f471-4f18-8958-52d7d94900ca.jpg"></div><div class="MomentCard__Text"><div class="MomentCard__CardTitle">Birthday</div><div class="MomentCard__CardDescription">Every birthday is worthy to be celebrated</div></div><div class="MomentCard__CardArrow"><img src="https://cdn.sweetescape.com/misc/svg/ico_arrow_right_black.svg"></div></div>
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>
    export default {
        name: "Card"
    }
</script>

<style lang="scss" scoped>
.categories{
        margin-top: 7rem;
        // background: #f2f2f2;
        padding-bottom: 3rem;
        box-sizing: inherit;
    }
.container {
    margin-bottom: 50px;
}
.momentCard-title {
    color: #3a596d;
    font-size: 32px;
    font-weight: 500;
    height: 24px;
    letter-spacing: -.3px;
    line-height: 36px;
    height: auto;
}
.momentCard-subtitle {
    margin-top: 9px;
    color: #37393a;
    font-size: 18px;
    font-weight: 400;
    letter-spacing: .3px;
    line-height: 24px;
}
.momentCard-wrapper {
    margin-top: 32px;
}
.row {
    margin-left: -15px;
    margin-right: -15px;
}
.MomentCard__Container {
    position: relative;
    display: inline-block;
    padding-left: 0;
    padding-bottom: 10px;
    cursor: pointer;
}
.MomentCard__ImageBackground {
    min-width: 211px;
    min-height: 211px;
}
.MomentCard__Text {
    position: absolute;
    color: #37393a;
    top: 0;
    width: 100%;
    height: 100%;
}
.MomentCard__CardTitle {
    color: #37393a;
    // font-family: Gotham Bold;
    font-weight: 800;
    letter-spacing: -.18px;
    line-height: 22px;
    display: inline-block;
    font-size: 22px;
    padding: 36px 0 16px 24px;
}
.MomentCard__CardDescription {
    font-size: 14px;
    padding-left: 24px;
    max-width: 181px;
}
.MomentCard__ChildTitle {
    color: #37393a;
    font-size: 18px;
    letter-spacing: .3px;
    line-height: 16px;
    font-weight: 400;
    margin-top: 12px;
    display: inline-block;
}
.MomentCard__ChildTitle:hover {
    text-decoration: underline;
}
.MomentCard__CardArrow {
    position: absolute;
    display: inline-block;
    top: 32px;
    right: 70px;
}
.MomentCard__ArrowInside {
    display: inline-block;
    padding-left: 9px;
    width: 32px;
    height: 32px;
}
.MomentCard__ArrowInside img {
    width: 100%;
    vertical-align: sub;
}
.MomentCard__TitleRow {
    display: block;
}
.MomentCard__GroupLink {
    position: absolute;
    // bottom: 0;
    padding: 36px 0 36px 24px;
}
.card {
    position: relative;
    display: flex;
    flex-direction: column;
    min-width: 0;
    word-wrap: break-word;
    background-color: #fff;
    background-clip: border-box;
    border: 1px solid rgba(0, 0, 0, 0.125);
    border-radius: 0.25rem;
}
.card-link {
    text-decoration: none;
    transition: 0.4ms ease-in-out;
    transform: rotate(360deg);
}
.card-link:hover {
    transform: rotate(360deg);
}
.card-title {
    font-size: 22px;
    padding: 3px 0 16px 24px;
        transform: rotate(360deg);
}
.card-text {
    font-size: 14px;
    padding-left: 24px;
    max-width: 181px;
}
@media (min-width: 768px){
.momentCard__Title{
    font-size: 32px;
    line-height: 36px;}}
</style>
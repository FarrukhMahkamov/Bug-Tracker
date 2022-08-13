<script>
    
</script>

<div class="card">
    <div class="card_header">
        <div class="card_image">
            <img src="images/task_completed.svg" alt="Completed Tasks" width="34" height="34">
        </div>
        <div class="card_title">
            <h1>Completed Tasks</h1>
        </div>
        <div class="card_description">
            <span>08</span>
        </div>
    </div>
    <span class="card_line"></span>
    <div class="card_info">
        <div class="card_info--image">
            <img src="images/task_completed_vector.svg" alt="" width="115" height="50">
        </div>
        <div class="card_info--descriotion">
            <div class="--description_accent">
                <span>10+</span>
                <p>more</p>
            </div>
            <p class="--description_info">
                from last week
            </p>
        </div>
    </div>
</div>

<style>
    .card {
        margin-left: 20px;
        max-width: 244px;
        max-height: 210px;
        background: #FFFFFF;
        border-radius: 16px;
        display: flex;
        flex-direction: column;
        padding: 10px 20px;
    }
    .card_header {
        display: flex;
        align-items: center;
        margin-bottom: 15px;
        padding-top: 22px;
    }
    .card_title {
        margin-left: 12px;
    }
    .card_title h1{
        font-family: 'DM Sans';
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 21px;
        color: #8C97A8;
    }
    .card_description{
        margin-left: 35px;
    }
    .card_description span {
        font-family: 'DM Sans';
        font-style: normal;
        font-weight: 700;
        font-size: 22px;
        line-height: 29px;
        color: #1E1E1E;
    }
    .card_line {
        display: block;
        width: 284px;
        height: 1px;    
        background-color: #E8EDF1;
        margin-bottom: 30px;
    }
    .card_info {
        display: flex;
        justify-content: space-between;
        margin-bottom: 10px;
    }
    .card_info--descriotion {
        display: flex;
        flex-direction: column;
    }
    .--description_accent{
        display: flex;
        align-items: center;
        text-align: center;
    }
    .--description_accent span {
        font-family: 'DM Sans';
        font-style: normal;
        font-weight: 700;
        font-size: 16px;
        line-height: 21px;
        color: #299702;
    }
    .--description_accent p{
        font-family: 'DM Sans';
        font-style: normal;
        font-weight: 500;
        margin: 0;
        font-size: 16px;
        line-height: 21px;
        color: #768396;
    }
    .--description_info {
        font-family: 'DM Sans';
        font-style: normal;
        font-weight: 500;
        padding: 0;
        margin: 0;
        font-weight: 500;
        font-size: 16px;
        line-height: 21px;
        
        /* identical to box height */
        
        color: #768396;
        
        
    }
</style>
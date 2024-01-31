<script setup>
const {data} = await useFetch("/api/items");
const items = data._rawValue.data;

</script>

<template>
  <div>
    <AppHeader />
    <RecordDiv/>
    <BenefitsDiv />
    <FollowDiv />
    <BlockDiv/>
    <WorkZone />
    <OftenQuestions :items="items" />
    <InterviewWay />
    <QualityBlock />
    <HrConnect />
    <TheFooter />
  </div>
</template>
